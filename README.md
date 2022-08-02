# harvest-energy-level-1

Energy Harvesting macht Kabel zur Stromversorgung oder das Nachladen von Batterien in Geräten überflüssig. Dieses Prinzip der Energiegewinnung kann direkt zur Versorgung von kleinen elektronischen Systemen genutzt werden.

# Die bisher bekannten Möglichkeiten...

Bei der thermoelektrischen Energiegewinnung wird der Temperaturunterschied von einem warmen oder kalten Objekt zur Umgebung genutzt, um elektrische Energie zu gewinnen. Dabei wird der sogenannte Seebeck-Effekt genutzt.

Mechanische Bewegung, Druck oder Schwingungen können mit piezoelektrischen oder induktiven Generatoren in elektrische Spannungen umgewandelt werden. So können beispielsweise vorhandene Vibrationen an Maschinen oder Motoren genutzt werden, um kleine elektronische Geräte mit Energie zu versorgen.

Inkohärente optische Strahlung ist optische Strahlung aus künstlichen Quellen, die im Unterschied zu Laserstrahlung ohne feste Phasenbeziehung der elektromagnetischen Wellen ist.


# Ziel:
#
..... magnetische und optische Felder intelligent verheiraten und nutzbar machen ......

@ die weltweite Sitation ist ansporn neue Wege zu finden :-) ....



#
Optische Strahlung

Das Sachgebiet Optische Strahlung befasst sich mit der elektromagnetischen Strahlung im Wellenlängenbereich von 100 nm (ultraviolette Strahlung) bis 1 mm (fernes Infrarot).
#
Elektromagnetische Felder

Das Sachgebiet Elektromagnetische Felder befasst sich mit statischen elektrischen, statischen magnetischen sowie zeitveränderlichen elektrischen, magnetischen und elektromagnetischen Feldern mit Frequenzen bis 300 Gigahertz.
#


#Update ...
optische spiegelreflexe erkennen und nutzbar machen ist aktuell bereits möglich ....  

private void button1_Click(object sender, EventArgs e)
{
    SetSuspendState(PowerState.Suspend, false, false);
}
[DllImport("powrprof.dll")]
private static extern bool SetSuspendState(PowerState state, bool ForceCritical, bool DisableWakeEvent);

GeneratorModel for yakindu::cpp {

	statechart LightSwitch {

		feature Outlet {
			targetProject = "org.yakindu.sct.examples.codegen.cpp"
			targetFolder = "src-gen"
		}
	}
}


namespace sc {
namespace timer {

/*! \file Interface for state machines which use timed event triggers.
*/
class TimedInterface {
	public:
	
		virtual ~TimedInterface() = 0;
		
		/*! Set the timer service for the state machine. It must be set
		    externally on a timed state machine before a run cycle can be executed.
		*/
		virtual void setTimerService(sc::timer::TimerServiceInterface* timerService) = 0;
		
		/*! Returns the currently used timer service.
		*/
		virtual sc::timer::TimerServiceInterface* getTimerService() = 0;
		
		/*! Callback method if a time event occurred.
		*/
		virtual void raiseTimeEvent(sc_eventid event) = 0;
		
		/*! Method to retrieve the number of time events that can be 
			active at once in this state machine.
		*/
		virtual sc_integer getNumberOfParallelTimeEvents() = 0;
};
...

@es geht weiter 🦖 ...
