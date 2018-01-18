<Type Name="RecurrentSchedule" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule">
  <TypeSignature Language="C#" Value="public class RecurrentSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecurrentSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecurrentSchedule" />
  <TypeSignature Language="F#" Value="type RecurrentSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ca02e-101">プロファイルを開始するときのスケジュールに関する制約。</span><span class="sxs-lookup"><span data-stu-id="ca02e-101">The scheduling constraints for when the profile begins.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrentSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-102">RecurrentSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-102">Initializes a new instance of the RecurrentSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrentSchedule (string timeZone, System.Collections.Generic.IList&lt;string&gt; days, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; hours, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeZone, class System.Collections.Generic.IList`1&lt;string&gt; days, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; hours, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.Nullable{System.Int32}},System.Collections.Generic.IList{System.Nullable{System.Int32}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timeZone As String, days As IList(Of String), hours As IList(Of Nullable(Of Integer)), minutes As IList(Of Nullable(Of Integer)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule (timeZone, days, hours, minutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="days" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="hours" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
        <Parameter Name="minutes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="timeZone"><span data-ttu-id="ca02e-103">プロファイルの時間のタイム ゾーン。</span><span class="sxs-lookup"><span data-stu-id="ca02e-103">the timezone for the hours of the profile.</span></span>
            <span data-ttu-id="ca02e-104">有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央</span><span class="sxs-lookup"><span data-stu-id="ca02e-104">Some examples of valid timezones are: Dateline Standard Time, UTC-11, Hawaiian Standard Time, Alaskan Standard Time, Pacific Standard Time (Mexico), Pacific Standard Time, US Mountain Standard Time, Mountain Standard Time (Mexico), Mountain Standard Time, Central America Standard Time, Central Standard Time, Central Standard Time (Mexico), Canada Central Standard Time, SA Pacific Standard Time, Eastern Standard Time, US Eastern Standard Time, Venezuela Standard Time, Paraguay Standard Time, Atlantic Standard Time, Central Brazilian Standard Time, SA Western Standard Time, Pacific SA Standard Time, Newfoundland Standard Time, E. South America Standard Time, Argentina Standard Time, SA Eastern Standard Time, Greenland Standard Time, Montevideo Standard Time, Bahia Standard Time, UTC-02, Mid-Atlantic Standard Time, Azores Standard Time, Cape Verde Standard Time, Morocco Standard Time, UTC, GMT Standard Time, Greenwich Standard Time, W. Europe Standard Time, Central Europe Standard Time, Romance Standard Time, Central European Standard Time, W. Central Africa Standard Time, Namibia Standard Time, Jordan Standard Time, GTB Standard Time, Middle East Standard Time, Egypt Standard Time, Syria Standard Time, E. Europe Standard Time, South Africa Standard Time, FLE Standard Time, Turkey Standard Time, Israel Standard Time, Kaliningrad Standard Time, Libya Standard Time, Arabic Standard Time, Arab Standard Time, Belarus Standard Time, Russian Standard Time, E. Africa Standard Time, Iran Standard Time, Arabian Standard Time, Azerbaijan Standard Time, Russia Time Zone 3, Mauritius Standard Time, Georgian Standard Time, Caucasus Standard Time, Afghanistan Standard Time, West Asia Standard Time, Ekaterinburg Standard Time, Pakistan Standard Time, India Standard Time, Sri Lanka Standard Time, Nepal Standard Time, Central Asia Standard Time, Bangladesh Standard Time, N. Central Asia Standard Time, Myanmar Standard Time, SE Asia Standard Time, North Asia Standard Time, China Standard Time, North Asia East Standard Time, Singapore Standard Time, W. Australia Standard Time, Taipei Standard Time, Ulaanbaatar Standard Time, Tokyo Standard Time, Korea Standard Time, Yakutsk Standard Time, Cen.</span></span> <span data-ttu-id="ca02e-105">オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時</span><span class="sxs-lookup"><span data-stu-id="ca02e-105">Australia Standard Time, AUS Central Standard Time, E. Australia Standard Time, AUS Eastern Standard Time, West Pacific Standard Time, Tasmania Standard Time, Magadan Standard Time, Vladivostok Standard Time, Russia Time Zone 10, Central Pacific Standard Time, Russia Time Zone 11, New Zealand Standard Time, UTC+12, Fiji Standard Time, Kamchatka Standard Time, Tonga Standard Time, Samoa Standard Time, Line Islands Standard Time</span></span></param>
        <param name="days"><span data-ttu-id="ca02e-106">プロファイルが有効になる曜日のコレクション。</span><span class="sxs-lookup"><span data-stu-id="ca02e-106">the collection of days that the profile takes effect on.</span></span> <span data-ttu-id="ca02e-107">使用可能な値は、日曜日土曜日までからです。</span><span class="sxs-lookup"><span data-stu-id="ca02e-107">Possible values are Sunday through Saturday.</span></span></param>
        <param name="hours"><span data-ttu-id="ca02e-108">プロファイルが有効にする時間のコレクション。</span><span class="sxs-lookup"><span data-stu-id="ca02e-108">A collection of hours that the profile takes effect on.</span></span> <span data-ttu-id="ca02e-109">サポートされている値は 24 時間制では、0 ~ 23 (午前/午後の時刻はサポートされません)。</span><span class="sxs-lookup"><span data-stu-id="ca02e-109">Values supported are 0 to 23 on the 24-hour clock (AM/PM times are not supported).</span></span></param>
        <param name="minutes"><span data-ttu-id="ca02e-110">プロファイルが有効にする (分) のコレクション。</span><span class="sxs-lookup"><span data-stu-id="ca02e-110">A collection of minutes at which the profile takes effect at.</span></span></param>
        <summary>
            <span data-ttu-id="ca02e-111">RecurrentSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-111">Initializes a new instance of the RecurrentSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Days">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Days { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Days" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Days" />
      <MemberSignature Language="VB.NET" Value="Public Property Days As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Days : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Days" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="days")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-112">取得または、プロファイルが有効になる曜日のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-112">Gets or sets the collection of days that the profile takes effect on.</span></span> <span data-ttu-id="ca02e-113">使用可能な値は、日曜日土曜日までからです。</span><span class="sxs-lookup"><span data-stu-id="ca02e-113">Possible values are Sunday through Saturday.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hours">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Hours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Hours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Hours" />
      <MemberSignature Language="VB.NET" Value="Public Property Hours As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Hours : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Hours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-114">取得または、プロファイルが有効にする時間のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-114">Gets or sets a collection of hours that the profile takes effect on.</span></span> <span data-ttu-id="ca02e-115">サポートされている値は 24 時間制では、0 ~ 23 (午前/午後の時刻はサポートされません)。</span><span class="sxs-lookup"><span data-stu-id="ca02e-115">Values supported are 0 to 23 on the 24-hour clock (AM/PM times are not supported).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minutes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Minutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Minutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Minutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Minutes As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Minutes : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Minutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-116">取得またはプロファイルが有効にする (分) のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-116">Gets or sets a collection of minutes at which the profile takes effect at.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-117">取得またはプロファイルの時間のタイム ゾーンを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-117">Gets or sets the timezone for the hours of the profile.</span></span> <span data-ttu-id="ca02e-118">有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央</span><span class="sxs-lookup"><span data-stu-id="ca02e-118">Some examples of valid timezones are: Dateline Standard Time, UTC-11, Hawaiian Standard Time, Alaskan Standard Time, Pacific Standard Time (Mexico), Pacific Standard Time, US Mountain Standard Time, Mountain Standard Time (Mexico), Mountain Standard Time, Central America Standard Time, Central Standard Time, Central Standard Time (Mexico), Canada Central Standard Time, SA Pacific Standard Time, Eastern Standard Time, US Eastern Standard Time, Venezuela Standard Time, Paraguay Standard Time, Atlantic Standard Time, Central Brazilian Standard Time, SA Western Standard Time, Pacific SA Standard Time, Newfoundland Standard Time, E. South America Standard Time, Argentina Standard Time, SA Eastern Standard Time, Greenland Standard Time, Montevideo Standard Time, Bahia Standard Time, UTC-02, Mid-Atlantic Standard Time, Azores Standard Time, Cape Verde Standard Time, Morocco Standard Time, UTC, GMT Standard Time, Greenwich Standard Time, W. Europe Standard Time, Central Europe Standard Time, Romance Standard Time, Central European Standard Time, W. Central Africa Standard Time, Namibia Standard Time, Jordan Standard Time, GTB Standard Time, Middle East Standard Time, Egypt Standard Time, Syria Standard Time, E. Europe Standard Time, South Africa Standard Time, FLE Standard Time, Turkey Standard Time, Israel Standard Time, Kaliningrad Standard Time, Libya Standard Time, Arabic Standard Time, Arab Standard Time, Belarus Standard Time, Russian Standard Time, E. Africa Standard Time, Iran Standard Time, Arabian Standard Time, Azerbaijan Standard Time, Russia Time Zone 3, Mauritius Standard Time, Georgian Standard Time, Caucasus Standard Time, Afghanistan Standard Time, West Asia Standard Time, Ekaterinburg Standard Time, Pakistan Standard Time, India Standard Time, Sri Lanka Standard Time, Nepal Standard Time, Central Asia Standard Time, Bangladesh Standard Time, N. Central Asia Standard Time, Myanmar Standard Time, SE Asia Standard Time, North Asia Standard Time, China Standard Time, North Asia East Standard Time, Singapore Standard Time, W. Australia Standard Time, Taipei Standard Time, Ulaanbaatar Standard Time, Tokyo Standard Time, Korea Standard Time, Yakutsk Standard Time, Cen.</span></span> <span data-ttu-id="ca02e-119">オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時</span><span class="sxs-lookup"><span data-stu-id="ca02e-119">Australia Standard Time, AUS Central Standard Time, E. Australia Standard Time, AUS Eastern Standard Time, West Pacific Standard Time, Tasmania Standard Time, Magadan Standard Time, Vladivostok Standard Time, Russia Time Zone 10, Central Pacific Standard Time, Russia Time Zone 11, New Zealand Standard Time, UTC+12, Fiji Standard Time, Kamchatka Standard Time, Tonga Standard Time, Samoa Standard Time, Line Islands Standard Time</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="recurrentSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca02e-120">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ca02e-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ca02e-121">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca02e-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>