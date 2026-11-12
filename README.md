# Interstellar V7

Web proxy with multi-tab browser interface.

## Deployment

Railway can deploy this repository using the included Dockerfile. Create a new
Railway project from this GitHub repository; Railway will build the image and
provide the `PORT` environment variable automatically.

For local deployment:

```bash
git clone https://github.com/UseInterstellar/Interstellar-Astro
cd Interstellar-Astro
bun install && bun start
```

## Development

```bash
bun install && bun dev
```

## Tech Stack

- Astro 5 + React 19
- Fastify backend
- Scramjet proxy engine
- Tailwind CSS
