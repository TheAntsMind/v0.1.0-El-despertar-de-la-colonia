setup(
    name="hormigasais-seopack",
    version="0.1.0",
    author="Cristhiam Quiñonez",
    author_email="hola@hormigasais.com",
    description="Paquete SEO ligero y automatizable de TheAntsMind, desarrollado por HormigasAIS.",
    long_description=open("README.md").read(),
    long_description_content_type="text/markdown",
    url="https://join.slack.com/t/hormigas-ais/shared_invite/zt-33zssiv5x-WXs1_8mQ6_9m0O9g0VNgAA
",  # Reemplazá con el link del repo final
    packages=find_packages(where="src"),
    package_dir={"": "src"},
    install_requires=[
        "requests",
        "beautifulsoup4",
    ],
    classifiers=[
        "Programming Language :: Python :: 3",
        "Operating System :: OS Independent",
        "Topic :: Internet :: WWW/HTTP :: Indexing/Search",
        "License :: OSI Approved :: MIT License",
    ],
    python_requires=">=3.7",
)






Funciones iniciales sugeridas: 

• get_title(url) 

• extract_meta(url) 

• check_keywords(url, keywords) 

• generate_report(url)

