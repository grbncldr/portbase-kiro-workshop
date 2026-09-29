# Portbase Kiro Workshop

## Workshop Environment

https://catalog.us-east-1.prod.workshops.aws/join?access-code=4109-0813ea-13

### Fix for backend/scripts/prepare-lambda-packages.sh on linux

⏺ Fixed code for line 35-38:

          # Update the import path in the function file
          # This sed command replaces '../../common/middleware' with './middleware'
          # Using .bak extension for cross-platform compatibility (macOS and Linux)
          sed -i.bak "s|require('../../common/middleware')|require('./middleware')|g" $package_dir/$(basename $function_path)
          rm -f $package_dir/$(basename $function_path).bak

## Evaluation Link 

 https://www.metricsthatmatter.com/url/u.aspx?E0B42561F236867889
 
## Survey link
https://pulse.aws/survey/BJXJJHUY?p=0

![QR code for evaluation](qr.png)

## Support & Questions : 
Email : gerben@cloudar.nl

## Connnect 

Linkedin :  https://www.linkedin.com/in/gerbenvis



