vector<int> generate_random_array(int size, int min_val, int max_val) {
    random_device rd;
    mt19937 gen(rd());
    uniform_int_distribution<> distrib(min_val, max_val);

    vector<int> arr(size);
    for (int i = 0; i < size; ++i) {
        arr[i] = distrib(gen);
    }
    return arr;
}
