# U.S. Census Data API Documentation Site

An online documentation site and interactive API reference for the U.S. Census Bureau's Census Data API, converted from the original PDF user guide.

> [!NOTE]
> This is an unofficial documentation project created from the [Census Data API User Guide](https://www.census.gov/content/dam/Census/data/developers/api-user-guide/api-user-guide.pdf) (PDF, July 30, 2024). It is not affiliated with or endorsed by the U.S. Census Bureau.

**Live site:** [haugen-tech-docs.mintlify.site](https://haugen-tech-docs.mintlify.site/purpose)

## About the Project

I created this as a self-directed portfolio project to convert an existing PDF user guide into a modern, docs-as-code documentation site. The project includes:

- **User Guide**: The original guide converted to Markdown and split into individual pages. The structure and TOC match the original so existing users can find what they need.
- **API Reference**: An OpenAPI specification covering three Census datasets (Population Estimates, American Community Survey, and International Trade), with an interactive "Try it" panel for each endpoint.
- **Cross-Linking**: Each example in the user guide links to its matching endpoint in the API Reference.

## Tools Used

- **Mintlify**: Site build, hosting, and API reference generation
- **OpenAPI (YAML)**: API specification
- **MDX/Markdown**: Page content
- **Git/GitHub and SourceTree**: Version control and deployment

## Repository Structure

| File or Folder | Description |
| --- | --- |
| `docs.json` | Site settings and sidebar navigation |
| `openapi.yaml` | OpenAPI specification for the API Reference |
| `*.mdx` | User guide and overview pages |
| `images/` | Images used in the documentation |
| `logo/` | Site logo files |

## Author

David Haugen, Information Architect & Senior Technical Writer
[Portfolio](https://davidnhaugen-94.github.io/) • [LinkedIn](https://www.linkedin.com/in/davidnhaugen)