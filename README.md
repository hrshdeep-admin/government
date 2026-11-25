# Redesigning My Life — simple government repository
No scripts, API keys or local Git installation are required. Keep the repository private; review files before upload. The nine original PDFs are in Charters/ and searchable text copies are in each Framework.md. The copies are automatic text extractions, not amendments; consult the PDF if formatting is unclear. The supplied PDFs are unchanged. Prompt.md files are new short appointment prompts, not copies of separate user prompt files (none were supplied here). Replace them with your preferred prompts if desired, subject to privacy and safety.

## Browser setup
1. Extract the ZIP once. Upload the contents, not the ZIP, into the root of your private GitHub repository using Add file > Upload files (an empty repo may show an upload link). Commit the initial files.
2. Use an eligible AI interface with repository access. Test reading AGENTS.md, Parliament_Status.md and the designated ministry's files without writing anything. If using ChatGPT's standard GitHub connector, reading is supported but writing requires a suitable write-capable interface or manual GitHub edits. No extra local setup is needed for eligible Codex Cloud access.
3. Review and ratify the common protocol and proposed charters explicitly before starting. Do not alter the original PDFs to misrepresent their original statuses; record later decisions in Parliament_Status.md or a separate ratification record.
4. For season 001, use a branch named season-001. Follow Letter_of_Explanation.md. Review each proposed patch and ensure that the next task can read the relevant branch. Merge final changes only after approval. GitHub retains history, so never upload sensitive personal data.

## Test prompt
Read AGENTS.md, Parliament_Status.md and Ministries/MVPRA/Prompt.md. Explain the declaration freeze and identify the files needed for a session. Do not make changes.

## Appointment prompt
You are the Minister of [CODE] for Season [NUMBER], dated [YYYY-MM-DD], phase [Declaration/Legislation/Judicial review]. Read AGENTS.md, verify branch and phase, and retrieve only the necessary official files. Produce a concise proposal; do not edit main or merge anything.

## Limitations
No automated enforcement or testing against your live repository. Each AI task may have a separate workspace. Uncommitted edits from another task are not shared; use reviewed branch commits or explicit draft handoffs. If your chosen interface cannot select/read the season branch, pass the relevant text manually. Fresh chats reduce conversational context but not the cost of reading required files.
