VM_FILES = ColumnPicker.vm DrawUtil.vm FourWinsGame.vm IOUtil.vm Main.vm TokenColumn.vm

4wins.vm: ${VM_FILES}
	cat *.vm > 4wins.vm

%.vm: %.jack
	../tools/JackCompiler.sh $<

clean:
	rm *.vm