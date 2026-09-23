# Schedule

VB6 ActiveX task-scheduler control from Eduardo A. Morcillo (`axSchedule` / `tsksch.ocx`, Edanmo): wraps Scheduling Agent jobs and triggers; includes a `Test` harness project. Open `ScheduleCtrl.vbp` (and optionally `Test/Test.vbp`) in the VB6 IDE.

**Source last updated:** 1999-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX OCX, WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `axSchedule` (`ScheduleCtrl.vbp`) | VB6 | ActiveX OCX | Task Scheduler jobs/triggers control (`tsksch.ocx`) |
| `Test` (`Test/Test.vbp`) | VB6 | WinForms exe | Harness for the schedule control |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ScheduleCtrl.vbp`
- `Test/Test.vbp` (optional harness)

## Requirements

- Visual Basic 6.0 IDE
- Windows Scheduling Agent / Task Scheduler runtime for the OCX

## Attribution and provenance

Third-party control by Eduardo A. Morcillo (Edanmo). Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Schedule`.

## License

Original Edanmo license applies to the control. MIT © 2026 VaderConsulting for Dave Robinson's working-copy packaging. See `LICENSE` and any upstream notices in the tree.
