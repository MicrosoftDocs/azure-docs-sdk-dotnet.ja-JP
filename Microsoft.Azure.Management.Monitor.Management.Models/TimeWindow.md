<Type Name="TimeWindow" FullName="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow">
  <TypeSignature Language="C#" Value="public class TimeWindow" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TimeWindow extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow" />
  <TypeSignature Language="VB.NET" Value="Public Class TimeWindow" />
  <TypeSignature Language="F#" Value="type TimeWindow = class" />
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
            <span data-ttu-id="50f94-101">特定の日付/時刻プロファイル。</span><span class="sxs-lookup"><span data-stu-id="50f94-101">A specific date-time for the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeWindow ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.#ctor" />
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
            <span data-ttu-id="50f94-102">Timewindow プロパティ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="50f94-102">Initializes a new instance of the TimeWindow class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeWindow (DateTime start, DateTime end, string timeZone = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime start, valuetype System.DateTime end, string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.#ctor(System.DateTime,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As DateTime, end As DateTime, Optional timeZone As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow : DateTime * DateTime * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow (start, end, timeZone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.DateTime" />
        <Parameter Name="end" Type="System.DateTime" />
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="50f94-103">ISO 8601 形式でプロファイルの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="50f94-103">the start time for the profile in ISO 8601 format.</span></span></param>
        <param name="end"><span data-ttu-id="50f94-104">ISO 8601 形式で、プロファイルの終了時刻。</span><span class="sxs-lookup"><span data-stu-id="50f94-104">the end time for the profile in ISO 8601 format.</span></span></param>
        <param name="timeZone"><span data-ttu-id="50f94-105">プロファイルの開始と終了時刻のタイム ゾーン。</span><span class="sxs-lookup"><span data-stu-id="50f94-105">the timezone of the start and end times for the profile.</span></span> <span data-ttu-id="50f94-106">有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央</span><span class="sxs-lookup"><span data-stu-id="50f94-106">Some examples of valid timezones are: Dateline Standard Time, UTC-11, Hawaiian Standard Time, Alaskan Standard Time, Pacific Standard Time (Mexico), Pacific Standard Time, US Mountain Standard Time, Mountain Standard Time (Mexico), Mountain Standard Time, Central America Standard Time, Central Standard Time, Central Standard Time (Mexico), Canada Central Standard Time, SA Pacific Standard Time, Eastern Standard Time, US Eastern Standard Time, Venezuela Standard Time, Paraguay Standard Time, Atlantic Standard Time, Central Brazilian Standard Time, SA Western Standard Time, Pacific SA Standard Time, Newfoundland Standard Time, E. South America Standard Time, Argentina Standard Time, SA Eastern Standard Time, Greenland Standard Time, Montevideo Standard Time, Bahia Standard Time, UTC-02, Mid-Atlantic Standard Time, Azores Standard Time, Cape Verde Standard Time, Morocco Standard Time, UTC, GMT Standard Time, Greenwich Standard Time, W. Europe Standard Time, Central Europe Standard Time, Romance Standard Time, Central European Standard Time, W. Central Africa Standard Time, Namibia Standard Time, Jordan Standard Time, GTB Standard Time, Middle East Standard Time, Egypt Standard Time, Syria Standard Time, E. Europe Standard Time, South Africa Standard Time, FLE Standard Time, Turkey Standard Time, Israel Standard Time, Kaliningrad Standard Time, Libya Standard Time, Arabic Standard Time, Arab Standard Time, Belarus Standard Time, Russian Standard Time, E. Africa Standard Time, Iran Standard Time, Arabian Standard Time, Azerbaijan Standard Time, Russia Time Zone 3, Mauritius Standard Time, Georgian Standard Time, Caucasus Standard Time, Afghanistan Standard Time, West Asia Standard Time, Ekaterinburg Standard Time, Pakistan Standard Time, India Standard Time, Sri Lanka Standard Time, Nepal Standard Time, Central Asia Standard Time, Bangladesh Standard Time, N. Central Asia Standard Time, Myanmar Standard Time, SE Asia Standard Time, North Asia Standard Time, China Standard Time, North Asia East Standard Time, Singapore Standard Time, W. Australia Standard Time, Taipei Standard Time, Ulaanbaatar Standard Time, Tokyo Standard Time, Korea Standard Time, Yakutsk Standard Time, Cen.</span></span> <span data-ttu-id="50f94-107">オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時</span><span class="sxs-lookup"><span data-stu-id="50f94-107">Australia Standard Time, AUS Central Standard Time, E. Australia Standard Time, AUS Eastern Standard Time, West Pacific Standard Time, Tasmania Standard Time, Magadan Standard Time, Vladivostok Standard Time, Russia Time Zone 10, Central Pacific Standard Time, Russia Time Zone 11, New Zealand Standard Time, UTC+12, Fiji Standard Time, Kamchatka Standard Time, Tonga Standard Time, Samoa Standard Time, Line Islands Standard Time</span></span></param>
        <summary>
            <span data-ttu-id="50f94-108">Timewindow プロパティ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="50f94-108">Initializes a new instance of the TimeWindow class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public DateTime End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As DateTime" />
      <MemberSignature Language="F#" Value="member this.End : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f94-109">取得または ISO 8601 形式で、プロファイルの終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="50f94-109">Gets or sets the end time for the profile in ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public DateTime Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As DateTime" />
      <MemberSignature Language="F#" Value="member this.Start : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f94-110">取得または ISO 8601 形式で、プロファイルの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="50f94-110">Gets or sets the start time for the profile in ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.TimeZone" />
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
            <span data-ttu-id="50f94-111">取得またはプロファイルの開始と終了時刻のタイム ゾーンを設定します。</span><span class="sxs-lookup"><span data-stu-id="50f94-111">Gets or sets the timezone of the start and end times for the profile.</span></span> <span data-ttu-id="50f94-112">有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央</span><span class="sxs-lookup"><span data-stu-id="50f94-112">Some examples of valid timezones are: Dateline Standard Time, UTC-11, Hawaiian Standard Time, Alaskan Standard Time, Pacific Standard Time (Mexico), Pacific Standard Time, US Mountain Standard Time, Mountain Standard Time (Mexico), Mountain Standard Time, Central America Standard Time, Central Standard Time, Central Standard Time (Mexico), Canada Central Standard Time, SA Pacific Standard Time, Eastern Standard Time, US Eastern Standard Time, Venezuela Standard Time, Paraguay Standard Time, Atlantic Standard Time, Central Brazilian Standard Time, SA Western Standard Time, Pacific SA Standard Time, Newfoundland Standard Time, E. South America Standard Time, Argentina Standard Time, SA Eastern Standard Time, Greenland Standard Time, Montevideo Standard Time, Bahia Standard Time, UTC-02, Mid-Atlantic Standard Time, Azores Standard Time, Cape Verde Standard Time, Morocco Standard Time, UTC, GMT Standard Time, Greenwich Standard Time, W. Europe Standard Time, Central Europe Standard Time, Romance Standard Time, Central European Standard Time, W. Central Africa Standard Time, Namibia Standard Time, Jordan Standard Time, GTB Standard Time, Middle East Standard Time, Egypt Standard Time, Syria Standard Time, E. Europe Standard Time, South Africa Standard Time, FLE Standard Time, Turkey Standard Time, Israel Standard Time, Kaliningrad Standard Time, Libya Standard Time, Arabic Standard Time, Arab Standard Time, Belarus Standard Time, Russian Standard Time, E. Africa Standard Time, Iran Standard Time, Arabian Standard Time, Azerbaijan Standard Time, Russia Time Zone 3, Mauritius Standard Time, Georgian Standard Time, Caucasus Standard Time, Afghanistan Standard Time, West Asia Standard Time, Ekaterinburg Standard Time, Pakistan Standard Time, India Standard Time, Sri Lanka Standard Time, Nepal Standard Time, Central Asia Standard Time, Bangladesh Standard Time, N. Central Asia Standard Time, Myanmar Standard Time, SE Asia Standard Time, North Asia Standard Time, China Standard Time, North Asia East Standard Time, Singapore Standard Time, W. Australia Standard Time, Taipei Standard Time, Ulaanbaatar Standard Time, Tokyo Standard Time, Korea Standard Time, Yakutsk Standard Time, Cen.</span></span> <span data-ttu-id="50f94-113">オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時</span><span class="sxs-lookup"><span data-stu-id="50f94-113">Australia Standard Time, AUS Central Standard Time, E. Australia Standard Time, AUS Eastern Standard Time, West Pacific Standard Time, Tasmania Standard Time, Magadan Standard Time, Vladivostok Standard Time, Russia Time Zone 10, Central Pacific Standard Time, Russia Time Zone 11, New Zealand Standard Time, UTC+12, Fiji Standard Time, Kamchatka Standard Time, Tonga Standard Time, Samoa Standard Time, Line Islands Standard Time</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="timeWindow.Validate " />
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
            <span data-ttu-id="50f94-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="50f94-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="50f94-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="50f94-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>