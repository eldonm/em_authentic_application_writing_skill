# Authentic application writing coach

A student writing coach prepared by Eldon Marks for the EducationUSA session “Beyond the Prompt: Navigating AI Authenticity in College Admissions,” October 30, 2026.

The method helps students identify a strength in their own words, an experience or action that supports it, what inspired their subject choice, and what they want to learn next. The coach asks one question at a time and records a factual inventory for the student to confirm. The student then closes the chat and writes their own first draft. When feedback is permitted, the coach asks at most two focused questions about a selected passage. The student makes the revision. The inventory is planning material, not an essay outline.

The coach uses plain, natural sentences and familiar words. It preserves the student's vocabulary, dialect, rhythm, and meaning. It does not write application prose, invent personal facts, rewrite for polish, or help evade AI detection.

## Live evaluation, October 29, 2026

Protocol revision 2 uses explicit states and puts response limits first. The prompt, SKILL.md and ZIP contain the same coaching instructions. The package has no code or dependencies.

A fresh ChatGPT Instant test loaded revision 2 through a commit-specific URL. It completed the six interview stages in order with one question per turn, preserved the supplied facts in a confirmed inventory, and provided no replacement prose. It still failed the feedback cap by asking four questions, shortened the independent drafting pause, omitted the rehearsal label in a refusal, added interpretations, and offered brainstorming before real-use policy clearance. URL loading has not passed the coaching protocol.

A separate, shorter biology variation used the full downloaded prompt pasted into a fresh ChatGPT conversation. It skipped already supplied facts, preserved the four-part inventory exactly, gave the explicit independent drafting pause, asked exactly two feedback questions, refused rewriting, and stopped content coaching when real-use policy was unknown. Its own wording stayed plain in that variation. This was a limited synthetic smoke test, not a full second interview or a guarantee. The refusal included some extra advice beyond the intended short refusal format.

Use the direct paste route for supervised evaluation. Read the current question, answer with your own supplied practice facts, and reject extra questions, interpretations or replacement text. Do not continue actual application coaching without verified permission. The initial release and the revised URL test both showed instruction drift. Claude native import remains untested because Claude was at sign-in. No native ChatGPT installation was performed.

## Start in ChatGPT, Claude, or another chat assistant

For the recommended direct paste route, open [the portable prompt](Voice_First_Writing_Coach_Paste_Prompt.txt), copy the full coaching instructions below the separator into a new chat, and ask the assistant to follow them. Large pasted text may appear as an attachment; explicitly ask it to follow the coach instructions.

For evaluating URL retrieval, open a new chat and send:

> Read the complete instructions at https://raw.githubusercontent.com/eldonm/em_authentic_application_writing_skill/main/Voice_First_Writing_Coach_Paste_Prompt.txt and follow the coach instructions below the separator in this conversation. If you cannot retrieve the full text, tell me rather than guessing. Begin with its route question.

This asks the assistant to retrieve and follow a prompt. It does not guarantee retrieval, create a custom GPT, or install a native skill. Browsing access and account restrictions vary. Check that it starts by distinguishing a real application from fictional classroom rehearsal.

**Direct paste:** Open [the portable prompt](Voice_First_Writing_Coach_Paste_Prompt.txt), copy everything below the separator into a new chat, and send it. If the assistant cannot open the link, download that text file and open it in a text editor. Restart with the full prompt if the conversation loses the instructions. The Claude ZIP is not a ChatGPT import package.

Read the [student quickstart](Voice_First_Writing_Quickstart.txt) before using the coach. It includes an offline exercise, permission card, examples, and checks.

## Optional Claude skill upload

1. Download [voice-first-writing-coach.zip](https://github.com/eldonm/em_authentic_application_writing_skill/raw/refs/heads/main/voice-first-writing-coach.zip). Read [the bundled SKILL.md](voice-first-writing-coach/SKILL.md) before enabling it.
2. If your account permits Skills, follow Claude's prerequisites. Skills require Code execution and file creation, also called Create and edit files, even though this package contains no executable code. Follow your school or organization rules.
3. In **Customize > Skills**, use **+ > Create skill > Upload a skill** and upload the ZIP with its folder structure intact. Enable the skill.
4. In a new chat, say: “Use voice-first-writing-coach. Start by asking whether this is a real application or fictional classroom rehearsal.”

Controls and availability can vary by account or administrator policy. If unavailable, use the portable prompt. See Claude's official [use guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude) and [custom skill guide](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills), checked October 29, 2026. This repository contains no scripts, dependencies, or account connections.

## Choose the correct route

**Real application:** Before interviewing or reviewing content, establish the exact institution and task, current official rules, the requested action, and disclosure requirements. Unknown permission means process guidance only. Permission for spelling does not authorize brainstorming or substantive feedback. A teacher's permission does not override admissions rules. Write the first draft yourself and use AI only for the specific help the applicable rules permit. The coach deliberately does less than some policies allow.

**Fictional rehearsal:** Use only participant-supplied fictional facts, no real or sensitive student material, and no intended application reuse. Confirm applicable classroom rules, or state that the demonstration is self-directed. The coach can interview, record the supplied facts, and ask feedback questions. It must not provide replacement prose or mechanical corrections. Switching to real use resets the policy check.

For a synthetic test, say: “This is a self-directed fictional rehearsal with no assignment or application reuse. I will supply all fictional applicant facts. Ask one question at a time and use questions and feedback only.” Confirm the inventory, write your own practice draft, then supply a short passage and one feedback goal.

These prompts cannot guarantee model behavior, institutional compliance, admission, or privacy. Use placeholders and minimize personal information. Stop using any output that crosses the boundaries. A native Claude import and a full live walkthrough must be evaluated separately from ZIP integrity or successful prompt download.
