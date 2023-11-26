# files-community/Files

Here's what I have to do as to improving on Files codebase

## TO DO

### 1. Files.App.Actions

- [ ] Update DI definitions to be `private IUserSettingsService { get; } = Ioc.Default.GetRequiredService<IUserSettingsService>()`
- [ ] Add XML comments on class definitions
- [ ] Make classes sealed

### 2. Files.App.Assets

- [ ] Rename folders
- [ ] Move files from Files.App.Resources

### 3. Files.App.Converters

- [ ] Split out converter classes from Files.App.Converters.Converter class
- [ ] Add XML commens on class definitions

### 4. Files.App.Data

_N/A_

### 5. Files.App.Dialogs

- [ ] Add Storege, Archives, Git, Global folders

### 6. Files.App.Extensions

- [ ] Rename Fractions to be FractionExtesions

### 7. Files.App.Helpers

