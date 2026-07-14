# ArkNovum

## The Open Source Hobby Archive Platform

**Preserve what you build. Document what you love. Share your journey.**

ArkNovum is a self-hosted, modular hobby archive platform designed for enthusiasts who want a permanent digital home for their collections, projects, creations, and knowledge.

Whether you build Gunpla, race RC vehicles, design model railroads, paint miniatures, restore electronics, collect memorabilia, or explore any other passion, ArkNovum provides the tools to organize, document, preserve, and celebrate the things that matter to you.

---

# Table of Contents

- [Why ArkNovum Exists](#why-arknovum-exists)
- [The Vision](#the-vision)
- [Modular Plugin Architecture](#modular-plugin-architecture)
- [Gundam / Gunpla Archive Plugin](#gundam--gunpla-archive-plugin)
- [RC Vehicle Archive Plugin](#rc-vehicle-archive-plugin)
- [Model Railroad Archive Plugin](#model-railroad-archive-plugin)
- [Miniature Painting Archive Plugin](#miniature-painting-archive-plugin)
- [Self Hosted By Design](#self-hosted-by-design)
- [Knowledge Integration](#knowledge-integration)
- [Design Principles](#design-principles)
- [Future Goals](#future-goals)
- [Contributing](#contributing)
- [Project License & Usage Policy](#project-license--usage-policy)
- [Pro Plugins](#pro-plugins)
- [Project Status](#project-status)
- [Name Meaning](#name-meaning)
- [License](#license)

---

# Why ArkNovum Exists

Every hobby tells a story.

A collection is more than a list of items.

A project is more than the finished result.

A creation is more than the materials used to make it.

Behind every hobby exists a journey:

- The excitement of discovering something new
- The research before starting
- The skills learned along the way
- The challenges overcome
- The modifications and personal touches added
- The time invested
- The memories created

Today, much of hobby history is scattered across spreadsheets, social media posts, forums, cloud photo libraries, notes applications, and physical notebooks.

Important information gets lost.

Build logs disappear.

Collections become difficult to track.

Knowledge is trapped inside individual communities.

ArkNovum exists to provide a permanent, organized, self-hosted archive where hobbyists can preserve their work and their experiences.

---

# The Vision

ArkNovum is built around one simple idea:

> The things we create, collect, and dedicate our time to deserve to be preserved.

ArkNovum is not simply an inventory application.

It is a digital workshop journal, collection archive, project history, and personal knowledge base.

The platform itself remains hobby-agnostic.

The core system provides the foundation.

Plugins provide the specialized experience.

---

# Modular Plugin Architecture

ArkNovum uses a fully modular plugin-based design.

Instead of creating separate applications for every hobby, ArkNovum provides a unified platform where hobby communities can create specialized plugins.

Users can install only the hobbies they are interested in.

Plugins can be:

- Installed
- Enabled
- Disabled
- Updated
- Removed without affecting other plugins

A user can maintain a complete archive without being forced into features they do not need.

The core platform manages:

- Users
- Authentication
- Collections
- Media
- Search
- Tags
- Timelines
- Data storage
- Backup and export
- Plugin management

Individual plugins define:

- Hobby-specific categories
- Custom fields
- Tracking systems
- Workflows
- External integrations
- Specialized views

---

# Gundam / Gunpla Archive Plugin

The Gundam plugin is designed for builders and collectors who want to document their entire Gunpla journey.

From acquisition to completion, every stage of a build can be preserved.

## Collection Management

Track your entire collection including:

- Owned kits
- Wishlist items
- Future purchases
- Completed builds
- Unbuilt backlog
- Displayed models
- Retired projects
- Duplicate kits

Collection statistics can include:

- Total kits owned
- Completed build count
- Collection completion percentage
- Collection value
- Kits organized by grade
- Kits organized by series
- Kits organized by manufacturer
- Build history
- Purchase history
- Collection goals

ArkNovum allows collectors to visualize their progress and understand their collection growth over time.

---

## Kit Information

Store detailed information about every kit:

- Mobile suit name
- Series
- Manufacturer
- Release information
- Grade
- Scale
- Kit number
- Purchase date
- Purchase location
- Purchase price
- Reference information
- Images
- External knowledge sources

---

## Build Tracking

Document every step of the building process:

- Build start date
- Completion date
- Current progress
- Build status
- Work sessions
- Progress photos
- Notes
- Challenges encountered
- Techniques learned

Build stages can be tracked from initial purchase through final display.

---

## Build Logs

Create detailed records of each project:

- Assembly notes
- Modification history
- Painting progress
- Decal application
- Customization details
- Final review
- Lessons learned

Each completed build becomes a permanent record of the creative process.

---

## Customization Tracking

Document personal modifications:

- Kitbashing
- Scratch-built additions
- Custom parts
- 3D printed components
- Resin upgrades
- Weapon modifications
- Structural changes
- Custom designs

---

## Painting and Finishing

Maintain detailed finishing information:

- Paint brands
- Color recipes
- Primers
- Clear coats
- Weathering techniques
- Airbrush settings
- Painting methods
- Custom mixes

---

## Decal and Sticker Management

Track:

- Decals used
- Sticker placement
- Custom markings
- Application methods
- Replacement decals
- Reference images

---

## Reviews and Reflections

After completion, builders can record:

- Overall rating
- Build difficulty
- Favorite aspects
- Problems encountered
- Recommendations
- Personal thoughts

The goal is not only to record what was built, but how and why it was built.

---

# RC Vehicle Archive Plugin

The RC Vehicle plugin focuses on builders, racers, and hobbyists who maintain and customize remote-controlled vehicles.

Track:

- Brands
- Models
- Vehicle specifications
- Scale information
- Electronics
- Motors
- ESCs
- Batteries
- Tires
- Suspension setups
- Maintenance history
- Repairs
- Upgrades
- Replacement parts
- Performance notes

Additional tracking includes:

- Race history
- Event participation
- Vehicle setups
- Competition records
- Local hobby events
- Required equipment
- Performance improvements

The goal is to provide RC enthusiasts with a complete record of their vehicles, modifications, maintenance, and experiences.

---

# Model Railroad Archive Plugin

The Model Railroad plugin supports collectors, layout builders, and railroad enthusiasts.

Track:

- Locomotives
- Rolling stock
- Manufacturers
- Scales
- Track systems
- Layout projects
- Terrain creation
- Scenery work
- Weathering techniques
- Paint mixes
- Construction logs
- Exhibition history

Future capabilities include:

- Layout planning
- Track design tools
- Project documentation
- Event tracking

ArkNovum allows model railroaders to preserve not only their collection, but the story behind every layout and creation.

---

# Miniature Painting Archive Plugin

The Miniature Painting plugin is designed for painters, collectors, and tabletop hobbyists.

Track:

- Miniature collections
- Purchase information
- Themes
- Factions
- Paint schemes
- Color recipes
- Painting techniques
- Styles
- Progress history
- Completed projects

Document:

- Base coating
- Layering
- Highlighting
- Washing
- Dry brushing
- Edge highlighting
- Weathering
- Custom techniques

Each miniature becomes a documented piece of artwork with its own history and creative process.

---

# Self Hosted By Design

Your archive belongs to you.

ArkNovum is designed to run on your own infrastructure:

- Home servers
- NAS devices
- Docker environments
- Private cloud systems

ArkNovum does not require:

- Mandatory subscriptions
- Vendor-controlled storage
- External accounts
- Cloud dependency

Your collection should remain accessible for years to come.

---

# Knowledge Integration

ArkNovum separates shared knowledge from personal history.

External sources can provide:

- Manufacturer information
- Product details
- Reference materials
- Community knowledge
- Documentation

Your archive stores:

- Your ownership history
- Your builds
- Your modifications
- Your experiences
- Your personal notes

The community preserves information.

You preserve your story.

---

# Design Principles

## Data Ownership

Your data should always remain yours.

ArkNovum focuses on:

- Exportability
- Portability
- Long-term accessibility

Your archive should never be locked behind a service, subscription, or proprietary platform.

---

## Preserve The Process

The final result is only one part of the hobby.

The learning, experimentation, mistakes, improvements, and discoveries are equally valuable.

ArkNovum preserves the journey, not just the finished product.

---

## Community Driven

The best hobby knowledge comes from the people who practice the hobby.

ArkNovum encourages communities to build and maintain their own plugins, integrations, and knowledge systems.

---

## Built For Longevity

Collections and hobbies often last decades.

Projects are passed between generations.

ArkNovum is designed to preserve memories, knowledge, and craftsmanship for the long term.

---

# Future Goals

Potential future features include:

- Mobile applications
- Plugin marketplace
- Community plugin repository
- Advanced collection analytics
- AI-assisted identification
- Image recognition
- Public showcase pages
- Event discovery
- Community sharing
- Recommendation systems
- Manufacturer database integrations
- Expanded automation capabilities

---

# Contributing

ArkNovum welcomes contributions from:

- Developers
- Designers
- Hobbyists
- Documentation writers
- Plugin creators
- Community members

Whether you contribute code, ideas, documentation, testing, or hobby expertise, every contribution helps build a better archive.

Areas where contributions are especially valuable:

- Core platform development
- Plugin creation
- Documentation
- User interface improvements
- Database integrations
- Hobby-specific knowledge systems

---

# Project License & Usage Policy

ArkNovum is built with the goal of remaining accessible to hobbyists, developers, and communities while ensuring the project identity, contributors, and long-term sustainability are protected.

The ArkNovum core platform is freely available for personal use, self-hosted deployment, and modification.

Users and developers are encouraged to:

- Install ArkNovum on their own hardware
- Modify the source code for personal use
- Create community plugins
- Contribute improvements back to the project
- Share extensions and integrations with the community

However, the following protections apply:

- ArkNovum may not be rebranded or redistributed under another name without explicit permission.
- Derivative projects must provide clear attribution to the original ArkNovum project.
- Redistributed versions must include a link to the original ArkNovum source repository.
- The ArkNovum name, branding, logo, and official identity may not be used by unofficial forks.
- Commercial resale of ArkNovum or modified versions is not permitted without authorization.

These protections exist to maintain project trust, prevent confusion between official and unofficial versions, and ensure proper recognition of contributors.

---

# Pro Plugins

ArkNovum will remain free to use as a self-hosted hobby archive platform.

Future premium "Pro" plugins may be offered to provide advanced capabilities, specialized workflows, and additional integrations.

Pro plugins may include:

- Advanced analytics
- Automated collection management
- Expanded external database integrations
- AI-assisted organization
- Specialized hobby workflows
- Professional-grade tools
- Additional customization options

Each Pro plugin may have its own pricing based on:

- Development complexity
- Maintenance requirements
- External service costs
- Feature depth

Revenue from Pro plugins will help support continued ArkNovum development, infrastructure, documentation, and community resources.

---

# Project Status

ArkNovum is currently in the planning and architecture phase.

The project is being designed around:

- Modular architecture
- Self-hosting
- Data ownership
- Plugin flexibility
- Community development
- Long-term preservation

---

# Name Meaning

## ArkNovum

**Ark**

A vessel created to preserve and protect something valuable.

**Novum**

Latin for "new" or "a new beginning."

Together:

**ArkNovum represents a new vessel for preserving the things we create, collect, and cherish.**

---

# License

ArkNovum is built by hobbyists, for hobbyists.

The licensing model is designed to protect:

- The community
- Contributors
- Project identity
- Long-term sustainability

The ArkNovum project encourages collaboration, creativity, and community contributions while maintaining protections around the official project name, branding, and ecosystem.

For detailed usage requirements, attribution requirements, redistribution rules, and commercial usage limitations, refer to the **Project License & Usage Policy** section above.

---

# Final Thoughts

Hobbies are more than collections.

They are records of curiosity, creativity, learning, and personal achievement.

Every completed project represents time invested.

Every collection represents a journey.

Every creation represents a story.

ArkNovum exists to preserve those stories.

Whether you build a single model, maintain a lifelong collection, compete in events, create intricate layouts, or simply enjoy the process of making something with your hands, ArkNovum provides a place to document and preserve that experience.

Built by hobbyists.

Designed for preservation.

Created for the future.

**Welcome to ArkNovum.**
