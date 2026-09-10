# Source: https://docs.canvasflow.io/article/297-xflow-ftp-setup

# xFlow FTP Setup

To deliver PDF files to Canvasflow via FTP, you will require an **Access Key ID**, a **Secret Key** and a **Remote Path**.  This information will be provided to you by the Canvasflow support team upon request. The two keys must be used together to authenticate requests to the appropriate remote path.

The structure will look similar to the below:

**Access Key ID:** BKIA9SPMJHIEZF4WYOSO

**Secret Access Key:** 1Sq7abcdCVjcXn/Rq2hP6Cgj2HE+ef+asMjy+vYu

**Remote Path:** /canvasflow-remote-path

## Using FTP/SFTP clients that support Amazon S3

The easiest way to send files to Canvasflow is to use an FTP / SFTP client that supports Amazon S3. Some examples of compatible clients can be found below.

#### Compatible Clients

- [FileZilla (Pro edition)](https://filezilla-project.org/) (Windows, macOS, and Linux)
- [Cyberduck](https://cyberduck.io/) (Windows, macOS, and Linux)
- [WinSCP](https://winscp.net/eng/download.php) (Windows)
- [Transmit](https://panic.com/transmit/) (macOs)
- [ForkLift 3](https://binarynights.com/) (macOS)

### Configuring the client:

When configuring the client, you’ll need to enter the details provided to you by Canvasflow, making sure to set `S3` (or `Amazon S3`) as the protocol.

#### Example details:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/62e8c595ee1e310313f7ca5c/file-8pbw7c59dx.jpg)

**Protocol:** Amazon S3

**Address:** s3.amazonaws.com

**Access Key ID:** BKIA9SPMJHIEZF4WYOSO

**Secret Access Key:** 1Sq7qxbqCVjcXn/Rq2hU6Cgj2HE+ef+asMjy+vYu

**Remote Path:** /canvasflow-remote-path

### Notes

1. Ensure you include the ‘/’ in the remote path.

## Programmatic (API) Access

Canvasflow also supports programmatic API access.  Please [contact support](mailto:support@canvasflow.io) for more information if you require this service.

Still need help? [Contact Us](https://docs.canvasflow.io/article/297-xflow-ftp-setup#) [Contact Us](https://docs.canvasflow.io/article/297-xflow-ftp-setup#)

Last updated on June 9, 2025

No results found