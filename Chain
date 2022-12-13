def chain(*args):
    for seq in args:
        for iter in seq:
            yield iter


if __name__ == '__main__':
    print(list(chain([1, 2, 3], ['a', 'b'], [42, 13, 7])))
