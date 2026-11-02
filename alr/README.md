<div align="center">

# ALR Repository

Official Alien Addon Packages for the Voyager Registry.

</div>

---

## About

This repository contains all officially accepted Alien Registration Packages (`.alr`) used by the Voyager Registry.

Files are created inside **VoyagerOS**, validated locally, and submitted here through GitHub Pull Requests. Once accepted, they become part of the official Registry and are available to every VoyagerOS installation.

---

## Submitting an alr

1. Draw a specimen in **Paint**, then choose **File Alien Registration**.
2. Complete the observation and choose **Create Observation Package**. It is saved in VoyagerOS under `/alr`.
3. Open **Alien Registry → Contribute**. Check that the package is marked **Valid**, then choose **Prepare** to download it.
4. Fork this repository.
5. Upload the downloaded `.alr` file to the **alr/** folder on a new branch in your fork.
6. Commit your changes using a clear commit message.
7. Open a Pull Request back to this repository, targeting **main**.

To reopen a package from your computer, use **Open .alr package** in the Contribute tab, or drop it there. It is validated before being saved locally.

Local observations are stored in this browser. Keep the downloaded package as a backup before clearing browser data.

**One alr Package per Pull Request.**

**Do not rename or manually edit the `.alr` file after it has been created.**

---

## Review

Every submission is checked for:

- Valid alr Package
- Complete metadata
- Valid Registry Identifier
- Duplicate renders
- Repository compatibility

Changes may be requested before a submission is accepted.

---

## After Merge

Once merged:

- The alr becomes an Official alien.
- It appears in the Voyager Registry.
- VoyagerOS checks the official registry at startup. Use **check now** in Browse to refresh it during a session.
- The alien becomes searchable in VoyagerOS.

---

## Repository Structure

- **alr/** — Contains all accepted Observation Packages (`.alr`).

---

## License

No License
