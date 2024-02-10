# Reddit for desktop

Reddit for desktop is the same Reddit but for Windows as desktop application

It is a Reddit client for browsing Reddit on Windows.

Reddit is the place where people come together to have the most authentic and interesting conversations on the internet—Where gaming communities, nostalgic internet forums, bloggers, meme-makers, and fandoms mingle alongside video streamers, support groups, news junkies, armchair experts, seasoned professionals, and artists and creators of all types.

With over 100,000 communities about every topic you could think of (and a few you’d probably never think of if it wasn’t for the creativity of strangers on the internet), Reddit is the place where you can dive into anything and connect with people on any topic.


Reddit desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Reddit App on your Windows platform Desktop or Laptop.

## Installation

To get Reddit desktop for Windows, you can [Download Reddit desktop installer]().

Or you can check the [releases]() page.

## Usage

Run the "Reddit.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Reddit desktop\Reddit desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
