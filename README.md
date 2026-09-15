def find_missing_number(numbers):
    expected = set(range(1, len(numbers) + 2))
    actual = set(numbers)

    return (expected - actual).pop()


if __name__ == "__main__":
    values = [1, 2, 3, 5, 6, 7]
    print("Values:", values)
    print("Missing number:", find_missing_number(values))
