# Portbase Kiro Workshop

## Workshop Environment

https://catalog.us-east-1.prod.workshops.aws/join?access-code=58bc-0bb01f-9e

## Fix for backend/scripts/prepare-lambda-packages.sh on linux

⏺ Fixed code for line 35-38:

          # Update the import path in the function file
          # This sed command replaces '../../common/middleware' with './middleware'
          # Using .bak extension for cross-platform compatibility (macOS and Linux)
          sed -i.bak "s|require('../../common/middleware')|require('./middleware')|g" $package_dir/$(basename $function_path)
          rm -f $package_dir/$(basename $function_path).bak

## Evaluation Link 

https://www.metricsthatmatter.com/url/u.aspx?DA6CF3DBB240902532
 
## Survey link
https://pulse.amazon/survey/BJXJJHUY

![QR code for evaluation](qr.png)

## Support & Question 
gerben@cloudar.nl

https://www.linkedin.com/in/gerbenvis



