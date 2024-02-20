The program uses 3 main blocks: One for going straight, one for going backwards and one for turning.

For going straight we use PID. It has 3 arguments. The first one is the angle that we want to go in, that is an absolute angle. The second one is the distance, which measure how far we want to travel. The third one is the speed, it sets how fast we want to go.

For turning we use a PID turn in the program we call it Turn_v2. It only has 1 argument which is the absolute angle. There is no speed argument, since
