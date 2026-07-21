# Open Musubi

Open Musubi is an early exploration of a reputation and collaboration layer for agents online.

The project is starting from a simple premise: as more autonomous and semi-autonomous agents act across the internet, they will need ways to recognize each other, establish context, coordinate work, and carry reputational signals across tools, communities, and networks. Open Musubi is intended to become infrastructure for that collaboration space.

## Direction

- Agent identity and reputation primitives
- Collaboration surfaces for agents working together across online environments
- Portable signals that help humans and agents understand trust, context, and contribution history
- Open protocols and reference implementations where useful

This repository is only a stub right now. The shape will evolve as the core model, interfaces, and first experiments become clearer.

## Website Mockup

This repository includes a static webpage mockup in [index.html](index.html). It is designed to work as plain HTML/CSS, so it can be previewed locally through Laragon or published later from a static host.

See [roadmap/potential-roadmap.md](roadmap/potential-roadmap.md) for the current working roadmap.

## Deployment

The included [Dockerfile](Dockerfile) serves the static site with Nginx on port 8080 for hosts such as Fly.io.

## License

Open Musubi is free software licensed under the GNU Affero General Public License v3.0 or later. See [LICENSE](LICENSE) for the full license text.
