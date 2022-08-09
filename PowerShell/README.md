# PowerShell Configurations

## Steps

- Install **PowerShell** using **Microsoft Store**

- Install WSL using **PowerShell** command

  ```
  wsl --install
  ```

- Install Linux from Microsoft Store

- Download and Install [Nerd Fonts](https://www.nerdfonts.com/) (CaskaydiaCove Nerd Font)

- Install the shell theme from [Oh My Posh](https://ohmyposh.dev/)

  ```
  winget install JanDeDobbeleer.OhMyPosh -s winget
  ```

- Download the OhMyPosh theme

  ```
  Get-PoshThemes
  ```

- Create the PowerShell profile, if its already not exists

  ```
  echo $PROFILE
  %HOMEPATH%\Documents\PowerShell\Microsoft.PowerShell_profile.ps1
  C:\Users\<UserName>\Documents\PowerShell\Microsoft.PowerShell_profile.ps1
  ```

- Update the PowserShell profile by adding the below line

  ```
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\jandedobbeleer.omp.json" | Invoke-Expression
  ```

- Update the **VSCode** settings to add the [Nerd Fonts](https://www.nerdfonts.com/) (CaskaydiaCove Nerd Font) to the **Font Family** settings

- Install the latest version of the PowerShell module **PSReadLine**

  ```
  Install-Module PSReadLine -RequiredVersion 2.2.5 -Force
  ```

- Install the latest version of the PowerShell module **Terminal-Icons**. [Blog Post](https://www.hanselman.com/blog/take-your-windows-terminal-and-powershell-to-the-next-level-with-terminal-icons)

  ```
  Install-Module -Name Terminal-Icons -Repository PSGallery
  ```

- Install the latest version of the PowerShell module **z** (Optional)

  ```
  Install-Module z -AllowClobber
  ```

- Tryout below [Oh My Posh](https://ohmyposh.dev/) themes
  ```
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\jandedobbeleer.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\markbull.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\ohmyposh.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\paradox.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\powerlevel10k_classic.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\sonicboom_dark.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\sonicboom_light.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\stelbent-compact.minimal.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\stelbent.minimal.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\takuya.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\thecyberden.omp.json" | Invoke-Expression
  oh-my-posh init pwsh --config="${env:POSH_THEMES_PATH}\tshangar.omp.json" | Invoke-Expression
  ```

---

## References

[YouTube tutorial](https://www.youtube.com/watch?v=VT2L1SXFq9U)
