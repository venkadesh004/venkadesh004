print("HELLO EVERYONE");

print("About Me");

void main() => runApp(AboutME());

class AboutME extends StatelessWidget {

  $(this).me({
    pronouns: HE || HIM,
    name: "S. Venkadesh",
    degree: "Pursuing BE in Computer Science Engineering",
    college: "Thiagarajar college of Engineering".
    hobby: hobby()
  });

  def hobby() {
    return "Love to learn new things!" + "Now doing " + doing();
  }

  def doing() {
    l = ["Web Development", "Mobile Application development", "ML", "DevOps", "Competitve Coding"];
    
    str = "";
    
    for (int i=0; i<l.length; i++) {
      str += l[i]+" ";
    }
    
    return str + "Languages I know "+ lang();
  }
  
  def lanng() {
    return "Python, JavaScript, c, Dart, Java, SQL, MongoDB, Bash, c++" + "Frameworks I Love "+ frame();
  }
  
  def frame() {
    return "Flutter, Node, Express, Flask, Django "+ end();
  }
  
  def end() {
    for (int i=0; i<100; i++) {
      print("Eat Learn Sleep");
    }
    
    return "Contact me @venkadesh-developer in instagram";
  }

}
