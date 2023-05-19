def tower_builder(n_floors):
    floor = n_floors + n_floors - 1
    return [f"{('*' * x).center(floor)}" for x in range(1, floor + 2, 2)]


