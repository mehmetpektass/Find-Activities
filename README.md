# Activity Finder 🎉

## Description

Activity Finder is a simple web application built using Express.js and EJS that helps you find random activities based on certain criteria. The application fetches random activities from an external API and allows users to filter activities by type and number of participants. Axios is used to make HTTP requests to the API, and the retrieved activities are rendered on the webpage using an EJS template.

## Installation and Using

1. Clone this repository to your local machine:
2. Navigate to the project directory.
3. Install dependencies by running:


```bash
import express from "express";
import bodyParser from "body-parser";
import axios from "axios";
...

1. Navigate to http://localhost:3000 in your web browser.
2. Select the type of activity and the number of participants from the dropdown menus.
3. Click the "Go" button to fetch a random activity based on your criteria.
4. The webpage will display the fetched activity along with its type and the number of participants.
```

```bash
cd /path/to/your/project

npm install express body-parser axios ejs

node index.js

```


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.🚀
