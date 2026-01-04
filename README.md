Datos de ejemplo para los ejercicios del curso.

- <a href="{{ site.baseurl }}/data/alanine-dipeptide.pdb">alanine-dipeptide.pdb</a>: estructura mínima para pruebas con OpenMM.
- <a href="{{ site.baseurl }}/data/alanine-dipeptide-multi.pdb">alanine-dipeptide-multi.pdb</a>: PDB multi-model para análisis de trayectorias sin DCD.
- <a href="{{ site.baseurl }}/data/example_rmsd.csv">example_rmsd.csv</a>: serie de RMSD de ejemplo para gráficas.
- <a href="{{ site.baseurl }}/data/complex/protein_orig.pdb">protein_orig.pdb</a>: proteína con ligando (preparación).
- <a href="{{ site.baseurl }}/data/complex/protein.pdb">protein.pdb</a>: proteína preparada para simulación.
- <a href="{{ site.baseurl }}/data/complex/ligand1.mol">ligand1.mol</a>: ligando en formato MOL.
- <a href="{{ site.baseurl }}/data/complex/ligand1.sdf">ligand1.sdf</a>: ligando en formato SDF.

## Generar trayectoria DCD

Para crear un DCD corto con OpenMM:

```bash
python scripts/generate_example_dcd.py
```

Esto genera <a href="{{ site.baseurl }}/data/alanine-dipeptide.dcd">alanine-dipeptide.dcd</a>.
