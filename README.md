[![Board Status](https://dev.azure.com/devopsbuild20190127/1dce1ccd-2b16-4f95-a77f-bebb687e939a/f6472dde-af75-4e3a-bbd2-d29337e167a5/_apis/work/boardbadge/f7c59ed9-7537-44f2-b367-7a5caa2437d2)](https://dev.azure.com/devopsbuild20190127/1dce1ccd-2b16-4f95-a77f-bebb687e939a/_boards/board/t/f6472dde-af75-4e3a-bbd2-d29337e167a5/Microsoft.RequirementCategory)
# Index Browser

A simple Windows application to display the contents of a Git repository's
index.  You can open a repository and display the file contents in the index
(the "stage").  By default, you view the files that are staged as the next
commit.

![Index Browser](docs/main.png)

You can display the full index entry for a record, to show the on-disk
information for the file in the working directory (the "cache").

![Item Details](docs/details.png)

You can also view the contents of the item as it exists in the index (in
[hexdump](https://github.com/ethomson/hexdump)'s canonical format).

![Item Contents](docs/contents.png)

## Technical Information

This is a .NET Core 3 application, utilizing WPF and
[libgit2](https://libgit2.org/) via .NET bindings.

This application is Copyright &copy; Edward Thomson and available under
the [MIT license](LICENSE).
