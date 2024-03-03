## Getting Started

First, run the development server:

add `output: "standalone"` inside next.config.mjs

```bash
npm run build
docker build . -t deploy-nextjs-to-gcp-cloundrun-using-docker:latest
docker run -p 3000:3000 deploy-nextjs-to-gcp-cloundrun-using-docker
```
