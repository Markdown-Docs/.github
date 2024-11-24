# **Markdown Docs Collaborative Editor** 🚀

A powerful, real-time collaborative Markdown editor inspired by Google Docs and Overleaf. Built with **React**, **Phoenix**, and **Haskell**, this project brings team-based editing to the next level with custom `.mds` format support, Unsplash image embeds, and live synchronization.

---

## **Key Features** 🌟

- **Real-Time Collaboration**:  
  Edit Markdown documents with your team simultaneously. See cursors and edits in real-time.  

- **Custom `.mds` Format**:  
  Extend Markdown with powerful features:
  - `!title[Your Title]`: Add beautiful document titles.  
  - `!gif[search term]`: Embed GIFs on the fly.  
  - `!image[unsplash term]`: Seamlessly add images from Unsplash.  

- **Live Preview**:  
  Instantly preview Markdown-rendered content as you type.

- **Unsplash Integration**:  
  Quickly embed stunning, royalty-free images.

- **History Tracking**:  
  Built-in undo/redo functionality.

---

## **Tech Stack** ⚙️

| **Component**   | **Technology**                           |
|------------------|------------------------------------------|
| **Frontend**     | [React](https://reactjs.org/), [CodeMirror](https://codemirror.net/), [react-markdown](https://github.com/remarkjs/react-markdown) |
| **Backend**      | [Phoenix Framework](https://www.phoenixframework.org/) |
| **Parser**       | [Haskell](https://www.haskell.org/) + [Pandoc](https://pandoc.org/) |
| **Database**     | PostgreSQL                              |
| **APIs**         | [Unsplash API](https://unsplash.com/developers) |

---

## **Usage** 📖

### 1. **Collaborative Editing**
- Share your document with team members. All changes are synchronized in real-time.

### 2. **Using `.mds` Features**
- Add titles:
  ```markdown
  !title[My Document Title]
  ```
- Embed a GIF:
  ```markdown
  !gif[coding cat]
  ```
- Add an Unsplash image:
  ```markdown
  !image[forest]
  ```

### 3. **Keyboard Shortcuts**
- `Ctrl + Z`: Undo  
- `Ctrl + Y`: Redo  
- `Ctrl + S`: Save Document  

---

## **Project Structure** 📂

```plaintext
markdown-docs/
├── frontend/        # React frontend
├── backend/         # Phoenix backend
├── parser/          # Haskell-based .mds parser
└── docs/            # Project documentation
```

---

## **Contributing** 🤝

We welcome contributions! Follow these steps to get started:  

1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature/awesome-feature`).  
3. Commit your changes (`git commit -m "Add awesome feature"`).  
4. Push to the branch (`git push origin feature/awesome-feature`).  
5. Open a pull request.

---

## **Roadmap** 🛤️

- [x] Basic Markdown editor with live preview.  
- [x] Real-time collaboration with WebSocket support.  
- [x] Custom `.mds` parser in Haskell.  
- [x] Unsplash API integration.  
- [ ] Export to PDF.  
- [ ] Mobile-friendly UI.  

---

## **License** 📜

This project is licensed under the [Apache License 2.0](LICENSE).  

---

## **Contributors** ✨

- **[Your Name](https://github.com/your-profile)**  
- **[Contributor 2](https://github.com/contributor2)**  
- **[Contributor 3](https://github.com/contributor3)**  
- **[Contributor 4](https://github.com/contributor4)**  

---

### **Demo Preview** 🎥

*Coming soon...*

For questions or feedback, feel free to [open an issue](https://github.com/Imtjl/markdown-docs/issues).  
