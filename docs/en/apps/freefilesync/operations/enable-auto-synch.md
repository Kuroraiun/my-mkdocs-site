# Enable automatic synchronization

Run a FreeFileSync backup automatically.

## Method 1: RealTimeSync

RealTimeSync monitors folders and runs synchronization when files change.

### Steps

1. Save the synchronization configuration.

    Click **File → Save As Batch Job**, then save the file as `.ffs_batch`.

2. Open **RealTimeSync**.

3. Click **Browse**, then select the `.ffs_batch` file.

4. Click **Start**.

RealTimeSync monitors the folders and runs synchronization when changes occur.

---

## Method 2: Windows Task Scheduler

Run synchronization at scheduled times.

### Steps

1. Save the synchronization configuration as a batch job.

    Click **File → Save As Batch Job**, then save the file as `.ffs_batch`.

2. Open **Task Scheduler**.

3. Click **Create Basic Task**.

4. Select the trigger (for example **Daily** or **At log on**).

5. Select **Start a program**.

6. Set the program to:

    ```
    FreeFileSync.exe
    ```

7. Add the `.ffs_batch` file as an argument.

The task will run the synchronization automatically.
