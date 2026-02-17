# khaoula-el-mekkaoui.github.io

Personal academic website for Khaoula El Mekkaoui.

🔗 **Live site:** [khaoula-el-mekkaoui.github.io](https://mekkhaoula.github.io/khaoula-el-mekkaoui.github.io/)

## About

PhD Candidate at Aalto University, incoming Senior Advisor at University of Turku. Research focus on federated learning, Bayesian machine learning, and computational genomics.

## Structure

```
├── index.html      # Main website (single file)
├── khaoula.png     # Profile photo
└── README.md
```

## Editing

### Update publications

Open `index.html` and find the `PUBLICATIONS` array. Add new entries:

```javascript
{
    title: "Paper Title",
    authors: "Author 1, Author 2, ...",
    venue: "Conference/Journal",
    year: 2025,
    links: {
        paper: "https://...",
        arxiv: "https://arxiv.org/abs/...",  // optional
        pdf: "https://..."                    // optional
    },
    thumb: null  // or thumbnail URL
}
```

### Update bio/contact

Edit the HTML directly in `index.html`. Sections are clearly labeled with comments.

### Change photo

Replace `khaoula.png` with a new image (keep the same filename, or update the `src` in index.html).

## Deploy

Push to `master` branch. GitHub Pages will automatically deploy.
