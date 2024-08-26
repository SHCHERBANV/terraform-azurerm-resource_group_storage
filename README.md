# Initialize Git repository

```
git init
```

# Add files to Git

```
git add main.tf variables.tf outputs.tf
```
# Create README.md
```
echo "# terraform-azurerm-resource_group_storage" > README.md
echo "## Usage" >> README.md
echo "This module creates an Azure resource group and a storage account." >> README.md

```

# Add LICENSE file (e.g., MIT License)
```
touch LICENSE
echo "MIT License" > LICENSE
```
# Create .gitignore

```
touch .gitignore
echo "*.tfstate" >> .gitignore
echo "*.tfstate.*" >> .gitignore
echo ".terraform/" >> .gitignore
```
# Add all files to Git
```
git add README.md LICENSE .gitignore
```
''' git commit -m "Initial commit" '''
