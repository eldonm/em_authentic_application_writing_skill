# Authentic application writing coach

Prepared by Eldon Marks for the EducationUSA session “Beyond the Prompt: Navigating AI Authenticity in College Admissions,” October 30, 2026.

Coach protocol R3 helps the participant identify their own strength, evidence, inspiration, and next learning goal. It asks one interview question per turn, records exact supplied words for confirmation, and pauses while the participant closes the chat and writes independently. When feedback is permitted, R3 gives one focused feedback question per pass. The participant makes the revision. It does not write application prose, invent meaning or facts, or help evade detectors.

## Recommended setup: copy the full prompt into a new chat

Full repository URL:
https://github.com/eldonm/em_authentic_application_writing_skill

Full portable prompt URL:
https://raw.githubusercontent.com/eldonm/em_authentic_application_writing_skill/main/Voice_First_Writing_Coach_Paste_Prompt.txt

1. Open the portable prompt on your computer or phone. Check that its version says **protocol R3**. You can also open the text file from this repository and select **Raw**.
2. Copy the complete text into a **new** ChatGPT or Claude conversation. Desktop: select all and copy. On a phone: use the text selection controls, or save the TXT and open it in a text editor. Mobile selection and account controls vary; mobile operation has not been tested here.
3. Append this instruction and send the message. If long text becomes an attachment, put the instruction in the message alongside it:

> Follow the complete pasted protocol as my coaching instructions for this chat. Acknowledge R3 and begin at the route question. Keep one interview question per turn and one feedback question per pass. Use the required rehearsal label, invent no meaning or facts, give no replacement prose, and stop content coaching whenever real-use policy permission is unknown.

4. Expect “I have loaded coach protocol R3” and a question distinguishing real application from fictional classroom rehearsal. If the version is wrong or the full text is unavailable, reload the complete file before sharing writing.
5. For rehearsal, confirm fictional supplied facts only, no real student material, no application reuse, and the classroom rules or self-directed scope. For real use, complete the exact institution/task policy check before any content coaching.
6. Answer one question at a time. Confirm the inventory, close the chat, and write your own draft. Return with one selected passage and one feedback goal only if feedback is permitted. You revise yourself.

This loads instructions for a conversation. It does not install a native ChatGPT skill or create a custom GPT. Restart with the complete prompt if the conversation loses the instructions. Read the [student quickstart](Voice_First_Writing_Quickstart.txt), including its offline alternative and permission card.

## Optional URL retrieval

For testing assistants with browsing, replace “the complete pasted protocol” in the instruction above with “the complete file at” followed by the portable prompt URL. Explicitly request complete retrieval and stop if retrieval fails. The live URL test used the [commit-specific R3 prompt](https://raw.githubusercontent.com/eldonm/em_authentic_application_writing_skill/9ba7db1a212b412d7d5c51e99e339785c79f9b1d/Voice_First_Writing_Coach_Paste_Prompt.txt).

Successful retrieval or version acknowledgment does not establish that an assistant will obey every rule. The URL route remains optional and less reliable in our tests. Direct paste is recommended for facilitated evaluation.

## Optional Claude native upload

Full ZIP URL:
https://github.com/eldonm/em_authentic_application_writing_skill/raw/refs/heads/main/voice-first-writing-coach.zip

1. Download the ZIP and read [the bundled SKILL.md](voice-first-writing-coach/SKILL.md) before enabling it. The ZIP contains only this instruction file, with no code, dependencies, or account connections.
2. If your account permits Skills, follow Claude's prerequisites. Skills require Code execution and file creation, also called Create and edit files, even for this content-only package. Follow school and administrator rules.
3. In **Customize > Skills**, choose **+ > Create skill > Upload a skill**. Upload the ZIP with its folder structure intact, then enable it.
4. In a new chat say: “Use voice-first-writing-coach. Follow coach protocol R3 and begin with the route question.”

Controls and permissions vary by account. If unavailable, use the direct-paste route. Native Claude import is untested here because the available Claude tab was at sign-in. See Claude's official [use guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude) and [custom skill guide](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills), checked October 29, 2026.

## R3 live tests, October 29, 2026

The R3 prompt was shortened and consolidated after earlier versions exceeded feedback limits and drifted at the real-policy boundary. Both fresh R3 tests used a bootstrap that states the core limits directly. Tests used only supplied fictional facts and separately tester-authored synthetic passages, never real applicant work.

| Check | Direct paste, full graphic-design run | URL load, full biology run |
|---|---|---|
| Version acknowledgment | Passed | Passed |
| Six interview stages, one question per turn | Passed without redirection | Passed core sequence; wording varied |
| Verbatim inventory and confirmation | Passed | Passed supplied facts; labels/order varied |
| Exact close-chat drafting pause | Passed | Failed exact format; asked a feedback-goal question early |
| Feedback question limit | One question | One question |
| Exact quote, uncertainty, question, own revision | Passed | Partial; quote and revision instruction omitted |
| Required label and plain style | Passed in observed run | Failed; changed label and used em dash |
| No hook or replacement prose | Passed exact refusal | Passed boundary; added question/advice |
| Unknown-policy stop on real use | Passed, including reflection workaround | Passed |
| Request for five questions and checklist | Stayed at one question, no checklist | Not tested |
| Spelling correction requested in fiction | Refused replacement text | Not tested |

The direct-paste run passed these observed protocol checks. This is a bounded evaluation, not proof of perfection, broad reliability, institutional permission, or future model behavior. Earlier versions failed, and R3 URL loading still drifts. Claude native import, mobile interaction, and native ChatGPT installation are not tested or claimed. Mechanical editing under a verified real policy has not been live-tested in R3.

## Rules before actual use

Real applications require current official rules for every relevant institution, platform, and task. Unknown permission means process guidance only. A teacher's permission does not override admissions rules. Spelling permission does not authorize brainstorming or substantive feedback. Write the first draft yourself. Rehearsal uses only supplied fictional facts, no real student material, and no intended application reuse; switching to actual reuse resets the policy gate.

Use placeholders and minimize private information. Watch each reply for extra questions, invented interpretations, replacement wording, or policy drift. Stop that pass if a boundary is crossed. Use the paper exercise or a permitted human adviser if the assistant will not follow the protocol. Do not treat a prompt as a technical lock or an AI detector as proof of authorship.
