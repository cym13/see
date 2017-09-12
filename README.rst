Description
===========

See is a video player wrapper to see videos from any source. If you don't
know how to get the video from a webpage, don't worry: it will find one.

Rationale
=========

Today, most websites use either flash or html5 to display videos. I do not
like looking at videos in a web browser: I already have a video player just
for this purpose. Getting it to play videos from any source, be it local or a
url is another step that 'see' is trying to take.

Documentation
=============
::

    Usage: see [PATH or URI]

Yes, that's all.

If you want to specify a specific way to get content from a website you can
write an extension: an example is available in the `Extensions' section in
the source code.

Dependencies
============

This script uses curl and depends on an external video player. I recommend
mpv for this purpose.

It also relies on nodejs for websites that dynamically build urls although it
is quite uncommon.

License
=======

This program is under the GPLv3 License.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

Contact
=======
::

    Main developper: Cédric Picard
    Email:           cedric.picard@efrei.net
