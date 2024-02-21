<p align="center">
  <a href="https://nitric.io">
    <img src="https://raw.githubusercontent.com/nitrictech/nitric/develop/docs/assets/nitric-logo.svg" width="120" alt="Nitric Logo"/>
  </a>
</p>

## About Nitric

[Nitric](https://nitric.io) is a multi-language framework for building cloud applications. Nitric applications let you define cloud resources inline and deploy to providers like AWS, Google Cloud and Microsoft Azure without writing custom infrastructure deployment code. Start by focusing on your product using standard nitric deployment providers for your cloud of choice, then customize as needed to maintain control.

Nitric makes it easy to:

- Build APIs, Websockets and Schedules in JavaScript, TypeScript, Python, Go and other languages
- Quickly create distributed apps, using async messaging, via Queues and Topics, between services
- Reliably deploy common cloud resources like Services, Buckets, Key/Value Stores, Queues, Secrets and Topics directly from application code
- Build or extend a deployment provider to deploy cloud resources as you see fit
- Deploy applications to different cloud services or cloud providers without changing core application code

### Example

Here's what it looks like to build and deploy an API gateway and a service to handle routes with Nitric:

```typescript
import { api } from "@nitric/sdk";

api("main").get("/hello/:name", async (ctx) => {
  const { name } = ctx.req.params;
  ctx.res.body = `Hello ${name}`;
});
```

Deploy this API with the `nitric up` command, without writing project specific IaC. 

```bash
nitric up
```

## Get in touch

- Ask questions in [GitHub discussions](https://github.com/nitrictech/nitric/discussions)

- Join us on [Discord](https://discord.gg/Webemece5C)

- Find us on [Twitter](https://twitter.com/nitric_io)

- Send us an [email](mailto:maintainers@nitric.io)
