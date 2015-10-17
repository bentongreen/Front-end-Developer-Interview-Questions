* What is event loop?

The event loop usually resembels this
while(queue.waitForMessage()){
  queue.processNextMessage();
}
It runs-to-completion meaning every message is processed completely before the next one, however this can cause problems if message takes too long.