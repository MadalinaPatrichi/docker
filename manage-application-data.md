# Manage application data

All the files that our application generates within our Docker container are stored ephemerally, since Docker containers are ephemeral themselves. Hence, there are a few examples of types of information that need to be persisted: databases, user-generated content from our application, logs, etc. 

By default, all data inside a Docker container is stored on a _writable container layer._ Here, 

#### Create Block Volume in OCI

We will attach a Block Volume to our OCI instance in order to use it to write data from our container. Find the `Menu / Core Infrastructure > Block Storage > Block Volumes` page.

![](.gitbook/assets/image%20%284%29.png)

 Note: Make sure that the block volume you want to create exists in the same Availability Domain as you VM instance.

![](.gitbook/assets/image%20%285%29.png)

![](.gitbook/assets/image%20%286%29.png)

![](.gitbook/assets/image%20%288%29.png)

