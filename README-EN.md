## 3Erefactor:  Effective, Efficient and Executable Refactoring Recommendation for Software Architectural Consistency

As software continues to evolve and business functions become increasingly complex, architectural inconsistency arises when the implementation architecture deviates from the expected architecture design. This architectural problem makes maintenance difficult and requires significant effort to refactor. To combat this problem, we have introduced the tool 3Erefactor, which is an intelligent refactoring recommendation tool specialized in removing architectural inconsistencies.

 ### Tool Core Functions:

   - Code Dependency Modeling and Visualization
   - Architecture Inconsistency Detection and Visualization
   - Automated Recommendations for Refactoring to Eliminate Architectural Inconsistencies
   - Interactive Code Refactoring


### Online Link to Tool Demo：
   Demo in Chinese Version：https://www.bilibili.com/video/BV1UN4y1k7pE/?spm_id_from=333.999.0.0

   Demo in English Version: https://youtu.be/8QMpd9TnsE0

### Description of repository structure:

   1. ##### "demo" folder
      - 3Erefactor-demo-video.MP4: The file is a demo video of the tool in Chinese Version. The English version is the video with the -EN suffix.
      - json-sample: Sample folder for feature usage, contains sample .json files for tool input.
      - sample-project: Sample project folder, containing java project files used for tool demo testing

   2. ##### "docs" folder

      - install-guide.md: A tool installation instruction document containing instructions for installing and debugging the tool.
      - usage-guide.md: A tool instruction document containing a detailed description of the tool's core functionality and instructions for use.

   3. ##### "install-package" folder
      - frontend: The folder for each version of the front-end installer .vsix file
      - backend: The folder  for each version of the backend installer .jar files.
      - These Installation files are stored using the GIT LFS protocol, please use the git pull command when pulling, using the zip package to get them may result in damage to the installation files.
