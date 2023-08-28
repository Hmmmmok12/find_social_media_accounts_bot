# What is this bot used for?
This bot is designed to query social media accounts including email, LinkedIn, Twitter, and Facebook of companies' executives from the Apollo rich database.

# Instruction
1. Open the input excel sheet file in ".\find_social_media_accounts_bot\input.xlsx" or create an input file of your own. The input file should look something like this. Note that the domain is the most important field and should not be null. <img src="instruction_images\input.jpg" alt="input file"/>
2. Input the Company Name (e.g.: Reddit), Company Domain (e.g.: reddit.com), and the Title of the person you want to find (e.g.: CEO).
3. Open the Application file stored in ".\find_social_media_accounts_bot\dist\main\main.exe". <img src="instruction_images\main.jpg" alt="main"/>
4. Run the application and a window will pop up. <img src="instruction_images\window.jpg" alt="window"/>
5. Input your Apollo API Key browse the input file and run the application. <img src="instruction_images\input_window.jpg" alt="input window"/>
6. When the application runs successfully, it will look like this. <img src="instruction_images\output_window.jpg" alt="output window"/>
7. After that you can check the output file. The output file will be stored in "\find_social_media_accounts_bot\dist\main\output_file.xlsx". <img src="instruction_images\output_path.jpg" alt="output path"/>
8. The output file content will look something like this. <img src="instruction_images\output.jpg" alt="output"/>

# Appendix
1. You should want to know how to create an Apollo API Key [here](https://knowledge.apollo.io/hc/en-us/articles/4415734629773-Configure-Access-to-the-Apollo-REST-API).
2. You must make sure that you will choose all API options. <img src="instruction_images\APIs_selection.jpg" alt="APIs selection"/>
3. This bot is built using [People Search API of Apollo](https://apolloio.github.io/apollo-api-docs/?python#search).
