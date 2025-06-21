# 🚀 Getting Started with Hacker Maui Template Studio

## 📦 Installation

### Via Visual Studio
1. Open **Extensions > Manage Extensions**
2. Search for "Hacker Maui Template Studio"
3. Click **Download** and restart VS

### Via Marketplace
<div align="start">
    <a href="https://marketplace.visualstudio.com/items?itemName=IngJorgePeralesDiaz.HackerMauiTemplateStudio">
    <img src="https://store-images.s-microsoft.com/image/apps.5031.1916fd4c-afe5-4d13-bb9a-3a92660536bd.f88e21e0-e4e1-449c-8c10-bce221a268be.ba6168c2-d22e-41d6-aefa-4108940aed56" alt="Sample screenshot" title="Visual Studio Marketplace" width="25"/>
Visual Studio Marketplace
</a>
</div>

### CLI Installation
```
dotnet new install HackerMauiTemplateStudio
```

🏗️ Creating a New Project

### Basic Command (Manual)
```
dotnet new hacker-maui -n MySecureApp -f net8.0 -a LayeredArchitecture
```

#### Full Options
```
dotnet new hacker-maui \
  --name YourAppName \
  --framework net8.0|net9 \
  --architecture LayeredArchitecture|None \
  --navigation Flyout|Tabs|Default \
  --codingstyle MVVM|CodeBehind \
  --features "EFCore,Refit,Serilog"
```

### Project Wizard

![HMTSCreateNewProj.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/image-af379401-86dc-4a49-8b2a-0f61c0b48272.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
  <br>

#### Provide the project name and select where it will be saved
![HMTSConfigureProject.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSConfigureProject-71b47758-cc3f-4623-a109-5893f169d9da.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### A new wizard will then guide you through creating the app you need

#### Select the version of .NET you want to target
![HMTSNetVersion.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSNetVersion-d02a5b4d-3433-4d37-898e-bc6874fed576.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### Do you want to apply an architectural pattern? Select it here
![HMTSArchitecture.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSArchitecture-18f7972d-fafe-4290-9d01-20286deaa0a3.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>

#### Pick a coding method that suits your development needs
![HMTSCoding.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSCoding-7c6301ae-503b-4a54-81a4-e7dd201e4c72.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### Decide on the navigation structure for your app
![HMTSNavigation.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSNavigation-1c418c18-d6f6-4aaf-8370-7753f86c660d.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### Select the pages or views you want to include in your app

#### Select pages with example content to help you get started, or opt for empty ones. You’ll also have the option to name your components

![HMTSPages.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSPages-27f16f65-8237-46d6-ae2c-6e1d30da02f3.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### Select any optional features you’d like to include
![HMTSFeatures.png](https://dev.azure.com/jpdmaui/74f34533-98f6-4f23-a235-f2d6b56b556e/_apis/git/repositories/01de5317-6f12-461e-a1e6-3e0c0c5beff6/Items?path=/.attachments/HMTSFeatures-0dfa02ff-bd0a-4511-af89-5dc230900ec4.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)
<br>
#### Finally, click 'Create' to generate a ready-to-use solution that jumpstarts your next great app—saving you valuable setup time

<br>
<br>

## 🔥 Key Features Quickstart
#### 1. Map Integration
```
// In your ViewModel
public Location UserLocation { get; } = new(47.6062, -122.3321);
```
#### In XAML
```
<maps:Map x:Name="map" 
          MapType="Street"
          IsShowingUser="True"/>
```
#### 2. API Client (Refit + Polly)
```
// Define interface
public interface IApiService
{
    [Get("/users/{id}")]
    Task<User> GetUserAsync(string id);
}

// Register with retry policy
builder.Services.AddRefitClient<IApiService>()
    .AddPolicyHandler(RetryPolicy);
```

#### 3. Performance Monitoring
```
// Add to MauiProgram.cs
builder.Services.AddSentry(options => {
    options.Dsn = "YOUR_DSN";
    options.TracesSampleRate = 1.0;
});
```

### 🛠️ Development Tips
#### Hot Reload Customization
```
// In .hotreload
{
  "$schema": "http://json.schemastore.org/hotreload",
  "watch": [ "**/*.xaml", "**/*.cs" ]
}
```
<br><br><br>
