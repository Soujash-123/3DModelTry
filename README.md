# 3D Model Animation Website

This repository contains the code for a 3D model animation website using Three.js.

## Prerequisites

- Node.js (v18.x)
- npm (comes with Node.js)

## Setup

1. Clone the repository:
   ```
   git clone [your-repo-url]
   cd web-3dmodel-threejs-main
   ```

2. Install dependencies:
   ```
   npm install three
   npm install -g http-server
   ```

## Running the Project

To run the project locally:

```
http-server
```

Then open your browser and navigate to `http://localhost:8080` (or the port specified by http-server).

## Troubleshooting

If you encounter issues related to the current working directory, such as:

```
Error: ENOENT: no such file or directory, uv_cwd
```

Try the following steps:

1. Ensure you're in the correct directory:
   ```
   pwd
   ```
   
2. If the issue persists, try changing to your home directory and then back:
   ```
   cd ~
   cd -
   ```

3. If problems continue, consider reinstalling Node.js and npm:
   ```
   sudo apt remove nodejs npm
   sudo apt update
   sudo apt install nodejs npm
   ```

## Notes

- This project uses Three.js for 3D graphics rendering.
- The `http-server` package is used to serve the website locally for development purposes.

## Contributing

[Add your contributing guidelines here]

## License

[Add your chosen license here]
