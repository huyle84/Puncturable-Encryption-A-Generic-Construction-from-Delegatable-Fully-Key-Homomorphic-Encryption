# Puncturable-Encryption-A-Generic-Construction-from-Delegatable-Fully-Key-Homomorphic-Encryption
ESORICS 2020-final version


Puncturable encryption (PE), proposed by Green and Miers at IEEE S\&P 2015, is a kind of public key encryption that  allows recipients to revoke individual messages by repeatedly updating decryption keys without communicating with senders. PE is an essential tool for constructing many interesting applications, such as asynchronous messaging systems,  forward-secret zero round-trip time protocols, public-key watermarking schemes and forward-secret proxy re-encryptions. This paper  revisits PEs  from the observation that the puncturing property can be implemented as efficiently computable functions. From this view, we propose a generic PE construction from the fully key-homomorphic encryption, augmented with a key delegation mechanism (DFKHE) from Boneh et al. at Eurocrypt 2014. We show that our PE construction enjoys the selective security under chosen plaintext attacks (that can be converted into the adaptive security with some efficiency loss)  from that of DFKHE in the standard model.  Basing on the framework, we obtain the first post-quantum secure PE instantiation that is based on the learning with errors problem, selective secure under chosen plaintext attacks (CPA) in the standard model. We also discuss about the ability of modification our framework to support the unbounded number of ciphertext tags inspired from the work of Brakerski and Vaikuntanathan at CRYPTO 2016.

\end{abstract}

