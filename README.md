# kiro-space

## Workshop Environment

https://catalog.us-east-1.prod.workshops.aws/join?access-code=d17e-0f5769-b1

## Fix for backend/scripts/prepare-lambda-packages.sh

⏺ Fixed code for line 35-38:

          # Update the import path in the function file
          # This sed command replaces '../../common/middleware' with './middleware'
          # Using .bak extension for cross-platform compatibility (macOS and Linux)
          sed -i.bak "s|require('../../common/middleware')|require('./middleware')|g" $package_dir/$(basename $function_path)
          rm -f $package_dir/$(basename $function_path).bak

## Evaluation Link 

https://www.metricsthatmatter.com/url/u.aspx?A39AA76DD233798085
