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
            プロファイルを開始するときのスケジュールに関する制約。
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
            RecurrentSchedule クラスの新しいインスタンスを初期化します。
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
        <param name="timeZone">プロファイルの時間のタイム ゾーン。
            有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央 オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時</param>
        <param name="days">プロファイルが有効になる曜日のコレクション。 使用可能な値は、日曜日土曜日までからです。</param>
        <param name="hours">プロファイルが有効にする時間のコレクション。 サポートされている値は 24 時間制では、0 ~ 23 (午前/午後の時刻はサポートされません)。</param>
        <param name="minutes">プロファイルが有効にする (分) のコレクション。</param>
        <summary>
            RecurrentSchedule クラスの新しいインスタンスを初期化します。
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
            取得または、プロファイルが有効になる曜日のコレクションを設定します。 使用可能な値は、日曜日土曜日までからです。
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
            取得または、プロファイルが有効にする時間のコレクションを設定します。 サポートされている値は 24 時間制では、0 ~ 23 (午前/午後の時刻はサポートされません)。
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
            取得またはプロファイルが有効にする (分) のコレクションを設定します。
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
            取得またはプロファイルの時間のタイム ゾーンを設定します。 有効なタイム ゾーンの例を示します: 日付変更線標準時 (utc)-11、ハワイ標準時、アラスカ標準時、太平洋標準時 (メキシコ)、太平洋標準時、米国山地標準時、山地標準時 (メキシコ)、山地標準時、中央アメリカ標準時、中部標準時、中部標準時 (メキシコ)、カナダ中部標準時、南アメリカ太平洋標準時、東部標準時、米国東部標準時、ベネズエラ標準時、パラグアイ標準時、大西洋標準時、中央ブラジル標準時、SA 西部標準時、太平洋南アメリカ標準時、ニューファンドランド標準時、南アメリカ東部標準時、アルゼンチン標準時、南アメリカ東部標準時、グリーンランド標準時、モンテビデオ標準時、Bahia 標準時、UTC 02、中央大西洋標準時、アゾレス諸島カーボベルデ標準時、標準時、モロッコ標準時、UTC、GMT 標準時、グリニッジ標準時、西ヨーロッパ標準時、中央ヨーロッパ標準時、ロマンス標準時、中央ヨーロピアン標準時、西中央アフリカ標準時、ナミビア標準時、ヨルダン標準時、GTB 標準時、中東標準時、エジプト標準時、シリア標準時、東ヨーロッパ標準時、南アフリカ標準時、FLE 標準時、トルコ標準時、イスラエル標準時、カリーニング ラード標準時、リビア標準時、アラビック標準時、アラブ標準時、ベラルーシ (標準時)、ロシア標準時、東アフリカ標準時、イラン標準時、アラビア標準時、アゼルバイジャン標準時、ロシア タイム ゾーン 3、モーリシャス標準時、グルジア標準時、コーカサス標準時、アフガニスタン標準時、西アジア標準時、エカテリンバーグ標準時、パキスタン標準時、インド スリランカ標準時、標準時、ネパール標準時、中央アジア標準時、バングラデシュ標準時、中央アジア北標準時、ミャンマー標準時、東南アジア標準時、北アジア標準時、中国の標準時、北アジア東標準時、シンガポール標準時、西オーストラリア標準時、台北 (標準時)、ウランバートル標準時、東京 (標準時)、韓国の標準時、ヤクーツク標準時、中央 オーストラリア標準時、AUS 中央標準時、東オーストラリア標準時、AUS 東部標準時、西太平洋標準時、タスマニア標準時、マガダン標準時、ウラジオストク標準時 (ロシア) タイム ゾーン 10、11 中央太平洋 (標準時)、ロシア タイム ゾーン、ニュージーランド標準時、UTC + 12、(標準時) フィジー、カムチャツカ標準時、トンガ標準時、サモア標準時、行諸島標準時
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>