# sparse_mat_reshuffle

    Parameters
    ----------
    mat : csr (sparse) matrix
    nodes_right : a list with the desired ordering 
    nodes_wrong : a list with the current ordering

    Returns
    -------
    A new csr matrix where columns and rows have
    been reordered to match the ordering contained in 
    nodes_right.
    It requires to specify the current order of nodes.
    -------
    notes:
    Created to rearrange adiacency Matrices in order
    to have them comparable across different layers of 
    the same graph.
