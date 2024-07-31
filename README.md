# snapshot-of-instance-and-create-volume-from-that-snapshot-attach-lifecycle-policy
Comprehensive Guide to Snapshot Management in AWS: Creating, Attaching, and Automating with Lifecycle Policies.
Launch an instance and then create a snapshot of that instance. Create a volume from that snapshot. Attach the created volume to the created instance and add lifecycle policy to it.

**Steps:**

Launch an instance.

Create a snapshot.

Create a snapshot, while creating a snapshot choose the Resource type as Instance. Give a description and create a snapshot.

Now, Create a volume from that snapshot. Select the snapshot and click on Actions then select Create volume from the snapshot.

The volume is created from the snapshot.

Attach the volume that is created from the snapshot. Go to Volumes, select the volume, click Actions, and select Attach Volume.

Attach this volume to the instance that is created. Select the instance and click on Attach Volume.

Create a Lifecycle policy.

The policy is created Successfully.
