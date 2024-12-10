**Initial Setup Guide**

1. Installing SASS:
```bash
npm i -g sass
```

2. Create the files and folders like in the repository except style.css and styles.css.map
   Short description about the folder structure:
   
   - ***Base Folder***
     In this folder, we usually define fundamental style like global typography, themes, variables, resets like setting margin and padding to 0.
     
  - ***Components***
    In this folder, we define styles for reusable components like buttons, dropdowns and also different body components an overall section like hero section.

  - ***Layout***
    In this folder, we usually define styles for overall layout like header, footer, navbar etc.

  - ***utils***
    In this folder we define different utilities like mixins and functions.

3. Now to watch the changes in main style.scss, use following command.
```bash
sass --watch style.scss style.css
```

4. Run the server

*Note* : The order in which the partial scss are imported in the main style.scss file matters. Please be careful the way you import the partials.
