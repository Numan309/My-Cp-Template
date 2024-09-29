C++ Code Template

This C++ code template is designed for competitive programming and includes a variety of useful features to streamline development. Below is a brief overview of the main components.
Features
Speed Optimizations

    Fast Input/Output: Uses ios_base::sync_with_stdio(false) and cin.tie(NULL) for efficient input and output.

Type Aliases

    Simplified types for ease of use:

    cpp

    using ll = long long;
    using lld = long double;
    using ull = unsigned long long;

Common Constants

    Defines commonly used constants like pi and a modulus for modular arithmetic:

    cpp

    const lld pi = 3.141592653589793238;
    const ll mod = 1e9 + 7;

Data Structures

    Includes various data structures such as vectors, pairs, and maps for convenience.

Macros

    A variety of macros to reduce code verbosity, including:
        ff: for looping through indices
        pb, mp: for manipulating vectors and pairs

Debugging

    Conditional debugging statements for easy output during development:

    cpp

    #ifdef NumanAkhtar
    #define debug(x) cerr << #x << " " << x << " "; cerr << endl;
    #else
    #define debug(x);
    #endif

Mathematical Utilities

    Functions for basic mathematical operations, including GCD, LCM, and modular exponentiation.

Graph Traversal

    Placeholder for depth-first search (DFS) with a simple graph representation.

Sorting and Checking Functions

    Includes sorting functions for pairs and utility functions to check primality and powers of two.

Main Function Structure

    The solve() function serves as the main problem-solving area, while the main() function handles input and manages test cases.

Usage

To use this template, simply copy the code and modify the solve() function according to the problem requirements. Make sure to customize any necessary sections for your specific needs.
