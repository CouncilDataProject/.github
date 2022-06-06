# CDP Deployments Monitor

| Instance    | Event Gather Status                                                                                                                                                                                                       |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Seattle     | [![Event Gather](https://github.com/CouncilDataProject/seattle/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/seattle/actions/workflows/event-gather-pipeline.yml)         |
| King County | [![Event Gather](https://github.com/CouncilDataProject/king-county/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/king-county/actions/workflows/event-gather-pipeline.yml) |
| Portland    | [![Event Gather](https://github.com/CouncilDataProject/portland/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/portland/actions/workflows/event-gather-pipeline.yml)       |
| Denver      | [![Event Gather](https://github.com/CouncilDataProject/denver/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/denver/actions/workflows/event-gather-pipeline.yml)           |
| Alameda     | [![Event Gather](https://github.com/CouncilDataProject/alameda/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/alameda/actions/workflows/event-gather-pipeline.yml)         |
| Boston      | [ ![Event Gather](https://github.com/CouncilDataProject/boston/actions/workflows/event-gather-pipeline.yml/badge.svg) ](https://github.com/CouncilDataProject/boston/actions/workflows/event-gather-pipeline.yml)         |

---

### Additions

To add a new instance to this README:

1. Go to: https://github.com/CouncilDataProject/{MUNICIPALITY-SLUG}/actions/workflows/event-gather-pipeline.yml with the `{MUNICIPALITY-SLUG}` filled in (i.e. king-county or seattle)
2. Click the `...` button in the top right
   ![GitHub Action page for a CDP instance looking at the "Event Gather" workflow history](./static/workflow-logs.png)
3. Click the "Copy status badge Markdown" button and paste it in to a new row in the table with the instance primary name
   ![GitHub Action workflow copy Markdown badge modal](./static/badge-modal.png)
