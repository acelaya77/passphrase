# passphrase

## Install

<details><summary> Windows Install </summary>

````powershell

$modules_path = Switch ( $PSVersionTable.PSEdition ){
   { $_ -match "Core" }{ (join-Path $([system.environment]::GetFolderpath("MyDocuments")) "Powershell") }
   Default { (join-Path $([system.environment]::GetFolderpath("MyDocuments")) "WindowsPowershell") }
}
$my_path = (join-Path $modules_path "New-Passphrase")

git clone git@github.com:acelaya77/passphrase.git $my_path

    ```

</details>
````
