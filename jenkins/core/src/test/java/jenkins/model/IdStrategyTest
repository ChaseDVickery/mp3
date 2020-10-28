
package jenkins.model;

import java.io.File;
import org.junit.Test;
import static org.junit.Assert.*;
import org.junit.Rule;
import org.junit.rules.TemporaryFolder;
import org.jvnet.hudson.test.Issue;

public class IdStrategyTest {

    @Test
    public void testidFromFilenameBasic() {
        String filename = "abcXYZ_. -";
        String id = CaseInsensitive.idFromFilename(filenam);
        assertEquals(filename, id);
    }

    @Test
    public void testidFromFilename() {
        String filename = "abc~a";
        String id = CaseInsensitive.idFromFilename(filename);
        assertEquals(id, "abcA");
    }
}