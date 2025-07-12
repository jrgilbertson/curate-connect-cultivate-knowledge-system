# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an Obsidian-based personal knowledge management system template called "Curate, Cultivate, Connect Knowledge System". It provides a structured approach to organizing notes, knowledge, and information using Obsidian's markdown-based system.

## Project Structure

The repository follows a specific folder hierarchy for knowledge organization:
- `Atomic Notes/` - Individual concept notes following Zettelkasten principles
- `Structure Notes/` - Index/Map of Content (MOC) notes that connect related concepts
- `Reference Notes/` - Notes from books, articles, and other external sources
- `Vocabulary Notes/` - Definitions and explanations of terms
- `People/` - Notes about individuals you interact with or study
- `Places and Things/` - Notes about locations, objects, and tools
- `Projects/` - Project documentation and planning
- `Meetings/` - Meeting notes and records
- `Jobs/` - Job opportunities and career-related information
- `Reviews/` - Periodic reviews and reflections
  - `Daily Notes/` - Daily journals and reflections
  - `Weekly Review/` - Weekly summaries and planning
  - `Quarterly Reviews/` - Quarterly assessments and goal setting
  - `Decisions/` - Decision logs and analysis
  - `Interviews/` - Interview notes and feedback
- `Inbox/` - Temporary storage for unprocessed notes
- `Attachments/` - Media files and attachments
- `Templates/` - Reusable templates for different note types

## Key Configuration

### Obsidian Configuration
- Configuration files are in `.obsidian/` directory
- `app.json` contains general settings
- `community-plugins.json` lists installed community plugins
- `workspace.json` defines the workspace layout

### Active Plugins
- Natural Language Dates - Parse natural language dates
- Periodic Notes - Daily/weekly note creation
- Calendar - Visual calendar interface
- Dataview - Query and display data from notes
- Linter - Markdown formatting and consistency
- Tag Wrangler - Tag management
- Outliner - Enhanced outline functionality

## Development Guidelines

### Working with Templates
Templates are markdown files in the `Templates/` folder that define the structure for new notes. When modifying templates:
- Preserve the YAML frontmatter structure
- Maintain consistent heading levels
- Keep placeholder text clear and instructional

### Note Naming Conventions
- Atomic Notes: `YYYYMMDDHHMM Title.md` (e.g., "202201101401 Structure notes create entry points.md")
- Daily Notes: `YYYY-MM-DD.md`
- People: `FirstName LastName.md`
- Projects/Meetings: Descriptive titles with dates where applicable

### Markdown Formatting
The Obsidian Linter plugin enforces consistent formatting. Key rules:
- Use standard markdown syntax
- Maintain consistent heading hierarchy
- Preserve wiki-style links `[[Note Title]]`
- Keep YAML frontmatter properly formatted

## Common Tasks

### Adding New Note Templates
1. Create a new markdown file in `Templates/` folder
2. Include appropriate YAML frontmatter
3. Use clear placeholders for dynamic content
4. Follow existing template patterns for consistency

### Modifying Folder Structure
When changing the organizational structure:
- Update any template files that reference specific folders
- Consider impact on existing Dataview queries
- Maintain logical hierarchy for knowledge organization

### Working with Obsidian Plugins
- Plugin configurations are in `.obsidian/` directory
- Community plugins listed in `community-plugins.json`
- Avoid modifying plugin data files directly

## Important Notes

- This is not a traditional software project - no build/test commands needed
- Focus on content organization and template structure
- Preserve Obsidian-specific syntax (wiki links, tags, etc.)
- The system is designed for personal knowledge management workflows