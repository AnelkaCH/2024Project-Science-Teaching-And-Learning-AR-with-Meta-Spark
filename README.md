# STeLAR (Science Teaching and Learning AR) 🔬

An augmented reality application built with Meta Spark Studio that turns printed science materials into interactive 3D learning experiences. Developed as a team project for the **UNTAR Meta Spark AR Competition 2024**, where it placed **1st**.

> Update (July 2026): Meta Spark Studio shut down in January 2025, so this project cannot be opened or run anymore. But we found some of the original project files saved on a laptop. They cannot be opened either, but they show how the project was built and are kept here for the record.


## What It Does

STeLAR uses image tracking to detect printed science pictures and overlays subject-specific 3D content on top of them in real time through a phone camera.

**Physics = Planet Gravity Simulation**
When a physics-related picture is scanned, a simulation of planetary gravity appears. Objects move according to gravitational pull, giving students a visual sense of how mass and distance affect gravity in the solar system.

**Chemistry = Water Formation Reaction**
When a chemistry picture is scanned (either of hydrogen or oxygen), an atomic model will be shown. If the pictures are arranged in a certain way, an animated molecular model shows two hydrogen atoms and one oxygen atom combining to form a water molecule (H2O). The animation walks through the bonding process step by step.

**Biology = 3D Cell Models**
When a biology picture is scanned (an animal cell or a plant cell) a labelled 3D model of the corresponding cell type appears. Students can view the structure from different angles.

## Built With

- **Meta Spark Studio** = the AR development platform (now discontinued)
- **Image Tracking / Target Tracking** = to recognise specific printed pictures and anchor AR content to them
- **3D Object Import** = pre-built 3D models loaded into the Spark environment
- **Animations** = keyframe and scripted animations for the molecule bonding and gravity sequences
- **Particle Effects** = used to add visual polish to the simulations

## Project Files

We built this project as three separate parts. I did the chemistry part, and my teammates did physics and biology. When they finished their parts, they sent me their files so I could put everything together into one final project.

These are the files we found:

- **phys module.arprojpkg** - the physics part, before it was combined
- **plant and animal cell.arprojpkg** - the biology part, before it was combined
- **STEM UNTAR SPARK AR.arprojpkg** - an early version of the combined project
- **WOA! STEM AR.arprojpkg** - the last and final version of the combined project

These files cannot be opened since the app that made them does not exist anymore. But we are keeping them here so people can see how the project came together, and so we do not lose them completely.

## What I Learned

This was my first real experience building something that had to work in the physical world, not just on a screen. A few things stood out:

**AR anchoring is harder than it looks.** Getting image tracking to stay stable when a phone moves around takes careful calibration of the target image and the scene. We went through several iterations on the tracking targets before the models stayed locked in place reliably.

**Constraints drive creativity.** Meta Spark had a relatively limited scripting environment compared to game engines. We had to find ways to simulate physics and chemistry concepts using the tools available, which meant thinking carefully about what visual approximation would actually teach something useful.

**Scope management for a team.** Three science subjects, each with its own 3D assets and interactions, was ambitious. We split work by module and had to sync on the overall UX so it felt consistent across all three. That coordination, more than the technical side, was the hardest part to get right.

**Communicating technical ideas to a non-technical audience.** A competition judging panel is not always technical. We had to present the educational purpose and the AR mechanics in a way that landed for both educators and engineers in the room.

## Screenshots

### Physics

<img width="298" height="593" alt="Sun" src="https://github.com/user-attachments/assets/4c82d2ee-f708-4745-a502-89fc74d43d64" />
<img width="298" height="593" alt="Earth" src="https://github.com/user-attachments/assets/855846b9-a86b-4da1-a977-57fd4b465af1" />
<img width="298" height="593" alt="Moon" src="https://github.com/user-attachments/assets/1f8bf76d-7d37-4477-8a51-c84ed1c93905" />
<img width="298" height="593" alt="Jupiter" src="https://github.com/user-attachments/assets/1fb86ce7-3e2b-4661-ab6c-a57e51838f47" />



### Chemistry

<img width="298" height="593" alt="HydrogenAtom" src="https://github.com/user-attachments/assets/657523e7-7051-4335-b41b-d2d5894e9d71" />
<img width="298" height="593" alt="OxygenAtom" src="https://github.com/user-attachments/assets/8929e407-e6a8-405e-9a61-e0eaaf432639" />
<img width="510" height="286" alt="H2OProduct" src="https://github.com/user-attachments/assets/a74c941e-d7e6-445a-a82b-2d5dc696ecfa" />
<img width="510" height="286" alt="H2OReaction" src="https://github.com/user-attachments/assets/b2845ba8-c027-447b-88cb-cb4182bf8c62" />


### Biology

<img width="450" height="800" alt="WhatsApp Image 2026-07-08 at 11 13 07 PM" src="https://github.com/user-attachments/assets/6bfda154-7ef7-4faa-aff0-b93a0563a1cd" />
<img width="450" height="800" alt="WhatsApp Image 2026-07-08 at 11 13 07 PM (1)" src="https://github.com/user-attachments/assets/4e4104c6-259d-4dee-9af7-40e94b7c3c63" />



## Team

Built as a team project at Bukit Sion Further Education (Year 10, 2024).
