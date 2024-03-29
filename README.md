# **Cite Our Work**
   Interface discription on https://arxiv.org/abs/2311.18203
   A Novel Interface Database of Graphene Nanoribbon from Density Functional Theory
   Ao Wu, Jiangxue Huang, Qijun Huang, Jin He, Hao Wang, Sheng Chang

 1. https://doi.org/10.1088/2632-2153/ad0937
    Ao Wu, et al., Graph machine learning framework for depicting wavefunction on interface. Machine Learning: Science and Technology, 2023.
 2. https://doi.org/10.1103/PhysRevApplied.12.044018
    Ye, S., et al., Wave-Function Symmetry Mechanism of Quantum-Well States in Graphene Nanoribbon Heterojunctions. Physical Review Applied, 2019. 12(4): p. 044018.
 3. https://doi.org/10.1103/PhysRevApplied.11.024026
    Lv, Y., et al., Interface Coupling as a Crucial Factor for Spatial Localization of Electronic States in a Heterojunction of Graphene      Nanoribbons. Physical Review Applied, 2019. 11(2).
# **Interface-Database Description**
 Interfaces play a crucial role in determining the overall performance and functionality of electronic devices and systems. We construct ample interface structures of graphene nanoribbons (GNR), whose interfacial morphology can be precisely fabricated based on specific molecular precursors.The GNR interfaces serve as promising candidates and their physical properties including energy bands and density of states (DOS) maps are obtained after the stress relief process. This database can provide theoretical guidance for the design of electronic devices and accelerate the ML study of various physical quantities.
# **Interface-Database Structure**
 The dataset contains three parts, Crystallographic Information File, ProjectedBandStructure, ProjectedDensityOfStates. Crystallographic Information File records the crystal structure, and we label the interface as
 ![Schematic diagram of the framework of the interface database](framework.png)

## **Interface-Database Crystallographic Information File (CIF)**
 Crystallographic Information File (CIF) is a computer file ending with ".cif", which contains information such as cell parameters, atomic coordinates, literature and so on. Various crystal and material processing software, such as Vesta, Diamond, Materials Studio, etc. use CIF as input or output.
 ![A schematic structure in the database. A-3-7-15-3 represents that it is the interface spliced by the triplet unit cells of 7AGNR and 15AGNR of the armchair boundary, which is modeled as the third one.](A-3-7-15-3.png)
 ``` crystal structure of the A-3-7-15-3
 # generated using pymatgen
 data_H32C132
 _symmetry_space_group_name_H-M   'P 1'
 _cell_length_a   20.00000000
 _cell_length_b   40.19450000
 _cell_length_c   26.16232944
 _cell_angle_alpha   90.00000000
 _cell_angle_beta   90.00000000
 _cell_angle_gamma   90.00000000
 _symmetry_Int_Tables_number   1
 _chemical_formula_structural   H8C33
 _chemical_formula_sum   'H32 C132'
 _cell_volume   21031.63501096
 _cell_formula_units_Z   4
 loop_
 _symmetry_equiv_pos_site_id
 _symmetry_equiv_pos_as_xyz
  1  'x, y, z'
 loop_
 _atom_site_type_symbol
 _atom_site_label
 _atom_site_symmetry_multiplicity
 _atom_site_fract_x
 _atom_site_fract_y
 _atom_site_fract_z
 _atom_site_occupancy
  C  C0  1  0.50000000  0.28476390  0.61721068  1
  C  C1  1  0.50000000  0.28691027  0.77607763  1
  C  C2  1  0.50000000  0.28307508  0.93514334  1
  C  C3  1  0.50000000  0.31592593  0.64113132  1
  C  C4  1  0.50000000  0.31677496  0.80375584  1
  C  C5  1  0.50000000  0.31215739  0.96340031  1
  C  C6  1  0.50000000  0.28308886  0.56473714  1
  C  C7  1  0.50000000  0.28694557  0.72376375  1
  C  C8  1  0.50000000  0.28477192  0.88266894  1
  C  C9  1  0.50000000  0.34805513  0.11261033  1
  C  C10  1  0.50000000  0.34622855  0.61235753  1
  C  C11  1  0.50000000  0.34734040  0.27625583  1
  C  C12  1  0.50000000  0.34749935  0.77733569  1
  C  C13  1  0.50000000  0.34795936  0.43943978  1
  C  C14  1  0.50000000  0.34480129  0.94270709  1
  C  C15  1  0.50000000  0.37780215  0.14033685  1
  C  C16  1  0.50000000  0.37750694  0.63914585  1
  C  C17  1  0.50000000  0.37746597  0.30455892  1
  C  C18  1  0.50000000  0.37797596  0.80548599  1
  C  C19  1  0.50000000  0.37662829  0.47149545  1
  C  C20  1  0.50000000  0.37592774  0.97248280  1
  C  C21  1  0.50000000  0.31219205  0.53653550  1
  C  C22  1  0.50000000  0.31681798  0.69612891  1
  C  C23  1  0.50000000  0.31593452  0.85878584  1
  C  C24  1  0.50000000  0.34807571  0.06038835  1
  C  C25  1  0.50000000  0.34480337  0.55728857  1
  C  C26  1  0.50000000  0.34732114  0.22370417  1
  C  C27  1  0.50000000  0.34752101  0.72261330  1
  C  C28  1  0.50000000  0.34804171  0.38722188  1
  C  C29  1  0.50000000  0.34623694  0.88763469  1
  C  C30  1  0.50000000  0.40774975  0.11137337  1
  C  C31  1  0.50000000  0.40769086  0.61072729  1
  C  C32  1  0.50000000  0.40790377  0.27750741  1
  C  C33  1  0.50000000  0.40843929  0.77787445  1
  C  C34  1  0.50000000  0.40753914  0.44422280  1
  C  C35  1  0.50000000  0.40699995  0.94515263  1
  C  C36  1  0.50000000  0.43826635  0.13917801  1
  C  C37  1  0.50000000  0.43875264  0.63835670  1
  C  C38  1  0.50000000  0.43823114  0.30591838  1
  C  C39  1  0.50000000  0.43893095  0.80598420  1
  C  C40  1  0.50000000  0.43832053  0.47216088  1
  C  C41  1  0.50000000  0.43833112  0.97280533  1
  C  C42  1  0.50000000  0.37675292  0.02843585  1
  C  C43  1  0.50000000  0.37588298  0.52746588  1
  C  C44  1  0.50000000  0.37744160  0.19537512  1
  C  C45  1  0.50000000  0.37799543  0.69448978  1
  C  C46  1  0.50000000  0.37781618  0.35959523  1
  C  C47  1  0.50000000  0.37750960  0.86083889  1
  C  C48  1  0.50000000  0.40762598  0.05577659  1
  C  C49  1  0.50000000  0.40696071  0.55480666  1
  C  C50  1  0.50000000  0.40789797  0.22244375  1
  C  C51  1  0.50000000  0.40844272  0.72212498  1
  C  C52  1  0.50000000  0.40772342  0.38862525  1
  C  C53  1  0.50000000  0.40770467  0.88924652  1
  C  C54  1  0.50000000  0.46881051  0.11146077  1
  C  C55  1  0.50000000  0.46948582  0.61085163  1
  C  C56  1  0.50000000  0.46856104  0.27751166  1
  C  C57  1  0.50000000  0.46942069  0.77777209  1
  C  C58  1  0.50000000  0.46908299  0.44417928  1
  C  C59  1  0.50000000  0.46969209  0.94515145  1
  C  C60  1  0.50000000  0.49862460  0.14066021  1
  C  C61  1  0.50000000  0.49999996  0.63948407  1
  C  C62  1  0.50000000  0.49900087  0.30447962  1
  C  C63  1  0.50000000  0.50006059  0.80518812  1
  C  C64  1  0.50000000  0.50003928  0.47145063  1
  C  C65  1  0.50000000  0.50056327  0.97250408  1
  C  C66  1  0.50000000  0.43839470  0.02783477  1
  C  C67  1  0.50000000  0.43828673  0.52717508  1
  C  C68  1  0.50000000  0.43825441  0.19408047  1
  C  C69  1  0.50000000  0.43892697  0.69401504  1
  C  C70  1  0.50000000  0.43822853  0.36082557  1
  C  C71  1  0.50000000  0.43876987  0.86164201  1
  C  C72  1  0.50000000  0.46915201  0.05583581  1
  C  C73  1  0.50000000  0.46965419  0.55482826  1
  C  C74  1  0.50000000  0.46857914  0.22252098  1
  C  C75  1  0.50000000  0.46942202  0.72221752  1
  C  C76  1  0.50000000  0.46876461  0.38856173  1
  C  C77  1  0.50000000  0.46951132  0.88913329  1
  C  C78  1  0.50000000  0.52835645  0.11315134  1
  C  C79  1  0.50000000  0.53091607  0.61296969  1
  C  C80  1  0.50000000  0.52917435  0.27630786  1
  C  C81  1  0.50000000  0.53075985  0.77740365  1
  C  C82  1  0.50000000  0.52860147  0.43901052  1
  C  C83  1  0.50000000  0.53149121  0.94238318  1
  C  C84  1  0.50000000  0.56164802  0.64116689  1
  C  C85  1  0.50000000  0.56160232  0.80422718  1
  C  C86  1  0.50000000  0.56303526  0.96400017  1
  C  C87  1  0.50000000  0.50010342  0.02852885  1
  C  C88  1  0.50000000  0.50052224  0.52746893  1
  C  C89  1  0.50000000  0.49904764  0.19559245  1
  C  C90  1  0.50000000  0.50006203  0.69478477  1
  C  C91  1  0.50000000  0.49858635  0.35940171  1
  C  C92  1  0.50000000  0.50002094  0.86049191  1
  C  C93  1  0.50000000  0.52865805  0.06100471  1
  C  C94  1  0.50000000  0.53146228  0.55756418  1
  C  C95  1  0.50000000  0.52921046  0.22381398  1
  C  C96  1  0.50000000  0.53074693  0.72255435  1
  C  C97  1  0.50000000  0.52833324  0.38686612  1
  C  C98  1  0.50000000  0.53093884  0.88698238  1
  C  C99  1  0.50000000  0.59305599  0.61596455  1
  C  C100  1  0.50000000  0.59267494  0.77726972  1
  C  C101  1  0.50000000  0.59337537  0.93807663  1
  C  C102  1  0.50000000  0.62390114  0.64191510  1
  C  C103  1  0.50000000  0.62372594  0.80361834  1
  C  C104  1  0.50000000  0.62316060  0.96589734  1
  C  C105  1  0.50000000  0.56300867  0.53594608  1
  C  C106  1  0.50000000  0.56159376  0.69570646  1
  C  C107  1  0.50000000  0.56167111  0.85877303  1
  C  C108  1  0.50000000  0.59334001  0.56186756  1
  C  C109  1  0.50000000  0.59267805  0.72264129  1
  C  C110  1  0.50000000  0.59308283  0.88396712  1
  C  C111  1  0.50000000  0.65444123  0.61380163  1
  C  C112  1  0.50000000  0.65486836  0.77715276  1
  C  C113  1  0.50000000  0.65404476  0.94101670  1
  C  C114  1  0.50000000  0.68568001  0.63961313  1
  C  C115  1  0.50000000  0.68562805  0.80454530  1
  C  C116  1  0.50000000  0.68444004  0.96865339  1
  C  C117  1  0.50000000  0.62308891  0.53397590  1
  C  C118  1  0.50000000  0.62371098  0.69625703  1
  C  C119  1  0.50000000  0.62391864  0.85796844  1
  C  C120  1  0.50000000  0.65397943  0.55880427  1
  C  C121  1  0.50000000  0.65486543  0.72266350  1
  C  C122  1  0.50000000  0.65447557  0.88602741  1
  C  C123  1  0.50000000  0.71509332  0.61051241  1
  C  C124  1  0.50000000  0.71539618  0.77633267  1
  C  C125  1  0.50000000  0.71453127  0.94287141  1
  C  C126  1  0.50000000  0.68434473  0.53110382  1
  C  C127  1  0.50000000  0.68561971  0.69523016  1
  C  C128  1  0.50000000  0.68569597  0.86015496  1
  C  C129  1  0.50000000  0.71444930  0.55682470  1
  C  C130  1  0.50000000  0.71539744  0.72342907  1
  C  C131  1  0.50000000  0.71513439  0.88918763  1
  H  H132  1  0.50000000  0.26173173  0.63911423  1
  H  H133  1  0.50000000  0.26284219  0.79516011  1
  H  H134  1  0.50000000  0.25907971  0.95505270  1
  H  H135  1  0.50000000  0.25910231  0.54480163  1
  H  H136  1  0.50000000  0.26293476  0.70453479  1
  H  H137  1  0.50000000  0.26178861  0.86065801  1
  H  H138  1  0.50000000  0.73928922  0.62956811  1
  H  H139  1  0.50000000  0.73935519  0.79611210  1
  H  H140  1  0.50000000  0.73802558  0.96420956  1
  H  H141  1  0.50000000  0.73792535  0.53544573  1
  H  H142  1  0.50000000  0.73934445  0.70362462  1
  H  H143  1  0.50000000  0.73928879  0.87001424  1
  H  H144  1  0.50000000  0.68335345  0.48925594  1
  H  H145  1  0.50000000  0.30678446  0.00338886  1
  H  H146  1  0.50000000  0.32390461  0.13175716  1
  H  H147  1  0.50000000  0.32340386  0.29599189  1
  H  H148  1  0.50000000  0.32319495  0.45399196  1
  H  H149  1  0.50000000  0.30692746  0.49652101  1
  H  H150  1  0.50000000  0.32338686  0.04560748  1
  H  H151  1  0.50000000  0.32335871  0.20404270  1
  H  H152  1  0.50000000  0.32396470  0.36784268  1
  H  H153  1  0.50000000  0.62221021  0.00780616  1
  H  H154  1  0.50000000  0.68347338  0.01050912  1
  H  H155  1  0.50000000  0.62210413  0.49205742  1
  H  H156  1  0.50000000  0.55243268  0.13246983  1
  H  H157  1  0.50000000  0.55308320  0.29607336  1
  H  H158  1  0.50000000  0.55370641  0.45213709  1
  H  H159  1  0.50000000  0.56726030  0.00407839  1
  H  H160  1  0.50000000  0.55380942  0.04804975  1
  H  H161  1  0.50000000  0.55316029  0.20415436  1
  H  H162  1  0.50000000  0.55237966  0.36745485  1
  H  H163  1  0.50000000  0.56735930  0.49588738  1
 ```

## **Interface-Database ProjectedBandStructure**
 Energy band theory is the idea that the electrons in a crystal are communized electrons moving throughout the crystal, and that the communized electrons are moving in the periodic potential field of the crystal; as a result, it is obtained that: the eigenstate wavefunction of the communized electrons is in the form of a Bloch function, and the energies are in the form of a number of energy bands made up of quasi-continuous energy levels. Energy band theory is the theoretical foundation of modern solid state electronics.

 We label the left and right parts **left** and **right**, respectively, and compute the projections of the energy bands onto these two parts and analyze how much they contribute to the total energy band.

 ![A-3-7-15-3-band](A-3-7-15-3-band.png)
 ![A-3-7-15-3-band_Projected](A-3-7-15-3-band_Projected.png)

## **Interface-Database ProjectedDensityOfStates**
 The density of states (DOS) is essentially the number of distinct states that an electron is allowed to occupy at a given energy level, i.e., the number of electronic states per unit energy unit of volume. We also project the distribution of the density of states over the two parts.

 ![A-3-7-15-3-DOS](A-3-7-15-3-DOS.png)

