## Credit
Jekyll builder: [timklapdor resume builder](https://github.com/timklapdor/resume-builder)

## How it works

Configuration is in the _config.yml file.

### Colour Configuration

Allows you to set all the colours used throughout the site without having to get into the CSS file. 

### Folder Structure

Each folder in the site contains a markdown file for each section. Folders of Awards, Education, Experience, Interests, Publications and Skills can contain multiple files. Use the same YAML structure as the dummy sections. 

The Profile section just has a single page. With the profiles listed you can remove or add them from the YAML front end, but you will also need to add/remove them from the index.html

## Customising

The Resume builder is completely customisable but you will have to do some editing. To create new sections - create new Collections in the config file, create new folders, and customise your YAML front end. 

The index file fairly clearly shows how to build a section. I've used IDs and Sections and then referred to them in the CSS (see bottom of the file) to create the alternative coloured sections. 

You can swap out the header image by changing the ```bgimage:``` in the config file. Centred images work best for the responsive design. 

### Pointing a URL 

[Github Pages Custom Domain](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)