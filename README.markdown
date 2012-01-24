Usage:

    wsd diagram.txt [target [format] [save_to_file [style]]]

	wsd diagram.txt diagram.txt png true napkin
	=> reads from diagram.txt, fetches png from wsd in napkin style and saves it to diagram.txt.png

    cat diagram.txt | wsd

    wsd http://gist.github.com/12371.txt
