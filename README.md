# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> Ollama Alfred Workflow

This workflow is a simple modification of the official Alfred OpenAI workflow for personal use with Ollama servers. The integration works by modifying the API endpoint to point to local Ollama instances instead of OpenAI's servers.

**Note:** This is a personal hack; many prompts and annotations were not cleaned up. 

--- 
Upstream README BELOW:
--- 

OpenAI integrations

[⤓ Install on the Alfred Gallery](https://alfred.app/workflows/alfredapp/openai)

## Setup

1. Create an OpenAI account and [log in](https://platform.openai.com/login?launch).
2. On the [API keys page](https://platform.openai.com/api-keys), click `+ Create new secret key`.
3. Name your new secret key and click `Create secret key`.
4. Copy your secret key and add it to the [Workflow's Configuration](https://www.alfredapp.com/help/workflows/user-configuration/).

## Usage

### ChatGPT

Query ChatGPT via the `chatgpt` keyword, the [Universal Action](https://www.alfredapp.com/help/features/universal-actions/), or the [Fallback Search](https://www.alfredapp.com/help/features/default-results/fallback-searches/).

![Start ChatGPT query](Workflow/images/about/chatgptkeyword.png)

![Querying ChatGPT](Workflow/images/about/chatgpttextview.png)

* <kbd>↩&#xFE0E;</kbd> Ask a new question.
* <kbd>⌘</kbd><kbd>↩&#xFE0E;</kbd> Clear and start new chat.
* <kbd>⌥</kbd><kbd>↩&#xFE0E;</kbd> Copy last answer.
* <kbd>⌃</kbd><kbd>↩&#xFE0E;</kbd> Copy full chat.
* <kbd>⇧</kbd><kbd>↩&#xFE0E;</kbd> Stop generating answer.

#### Chat History

View Chat History with ⌥↩&#xFE0E; in the `chatgpt` keyword. Each result shows the first question as the title and the last as the subtitle.

![Viewing chat histories](Workflow/images/about/chatgpthistory.png)

<kbd>↩&#xFE0E;</kbd> to archive the current chat and load the selected one. Older chats can be trashed with the `Delete` [Universal Action](https://www.alfredapp.com/help/features/universal-actions/). Select multiple chats with the [File Buffer](https://www.alfredapp.com/help/features/file-search/#file-buffer).

### DALL·E

Query DALL·E via the `dalle` keyword.

![Start DALL-E query](Workflow/images/about/dallekeyword.png)

![Querying DALL-E](Workflow/images/about/dalletextview.png)

* <kbd>↩&#xFE0E;</kbd> Send a new prompt.
* <kbd>⌘</kbd><kbd>↩&#xFE0E;</kbd> Archive images.
* <kbd>⌥</kbd><kbd>↩&#xFE0E;</kbd> Reveal last image in the Finder.
