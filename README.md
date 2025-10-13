# CCA Website

- **Installing and Deploying**: For installation and deployment details please refer to [INSTALL.md](INSTALL.md).

- **Customizing**: For customization details please refer to [CUSTOMIZE.md](CUSTOMIZE.md).

---

### About

- general information about out group: update in `_pages/about.md`
- newsfeed: to generate a new entry create a new file `_news/announcement_x.md`
- selected publications: to add/delete publications change `selected={true/false}` in `_bibliography/papers.bib`

---

### People

To add an entry:

- create a new branch first
- check if your markdown file already exists in `_pages/about/{name}.md`, create it if not
- fill in your information in this file
- go to `_pages/profiles.md` and look for the entry with your name, create it if not
- to create an entry, copy
  ```
    align: right
    image: generic_profile.jpg
    content: /about/{name}.md
    image_circular: true
    more_info: >
      <p>Room x.xxx</p>
      <p>mail@uni-goettingen.de</p>
  ```
  at the end of the list; alternate between left and right alignment
- to add a picture, upload a picture in `assets/img/` and replace `generic_profile.jpg` with your file name
- also adjust your room number and mail address
- make a PR

---

### Research

Keep? More information about different research projects?

---

### Publications

The publications' page is generated automatically from the BibTex bibliography: [\_bibliography/papers.bib](_bibliography/papers.bib).

---

### Repositories

Can be selected in `_data/repositories.yml`

---

### Teaching

Update in `_pages/teaching.md`

---

### CV

Keep? Delete?

---

For more info look at the original git repository: [alshedivat/al-folio](https://github.com/alshedivat/al-folio)
