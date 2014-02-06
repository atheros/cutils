all: test_dstr test_dstrutils


test_dstr: test_dstr.c ../src/dstr.c ../src/dstr.h tests_utils.c tests_utils.h
	$(CC) -o test_dstr test_dstr.c ../src/dstr.c tests_utils.c

test_dstrutils: test_dstrutils.c ../src/dstr.c ../src/dstr.h ../src/dstrutils.c ../src/dstrutils.h tests_utils.c tests_utils.h
	$(CC) -o test_dstrutils test_dstrutils.c ../src/dstrutils.c ../src/dstr.c tests_utils.c

