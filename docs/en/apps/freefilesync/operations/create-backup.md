# Create a backup

Synchronize files between a source folder and a backup folder.

## Steps

1. Select the source folder.

    Click **Browse** on the left side, then select the folder to back up.

2. Select the backup folder.

    Click **Browse** on the right side, then select the destination folder.

3. Click **Compare**.

    FreeFileSync scans both folders and displays the differences.

4. Select the synchronization mode.

    Click the **gear icon** next to **Synchronize**, then choose a mode.

5. Click **Synchronize**.

    The program copies the changed files to the backup folder.

## Synchronization modes

| Mode        | Description                                     |
| ----------- | ----------------------------------------------- |
| **Mirror**  | Destination becomes an exact copy of the source |
| **Update**  | Only new or updated files are copied            |
| **Two Way** | Changes are synchronized in both directions     |

## Optional

To reuse the configuration:

1. Click **File → Save As**.
2. Save the configuration as a `.ffs_gui` file.

Open the file later and click **Synchronize** to run the backup again.
