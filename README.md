# Installation
```
# Install yeoman
npm install -g yo

# Install Azure terraform module
npm install -g generator-az-terra-module
```

# Generate templates
```
# Create template folder
folderName=sampleTemplate
mkdir $folderName
cd $folderName

# Create terraform base module template
yo az-terra-module
```