suddenly, I was in need for neural network functionality in the serverside PostgreSQL context, but surprisingly found nothing out there.

So I grabbed the next NN library I found (fann) and ported it to the memory model of serverside PostgreSQL C, made NNs in-RAM & DB persistable/cloneable and added a session scoped NN cache that should make it fast in .

The thing is not production ready nor is it intended for admin user level - right now. I just hacked it together for the needs of my own applications.

You are welcome to have a early look and use it under GPL.

All credit for the implementation of NNs itself goes to the fann library project http://leenissen.dk/fann/wp/
Thanks.