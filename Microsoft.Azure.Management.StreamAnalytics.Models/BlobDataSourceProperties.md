<Type Name="BlobDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties">
  <TypeSignature Language="C#" Value="public class BlobDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobDataSourceProperties" />
  <TypeSignature Language="F#" Value="type BlobDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Blob のデータ ソースに関連付けられているプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BlobDataSourceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobDataSourceProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties (storageAccounts, container, pathPattern, dateFormat, timeFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="pathPattern" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccounts">1 つまたは複数の Azure ストレージ アカウントの一覧。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="container">関連付けられたストレージ アカウント内のコンテナーの名前。 このコンテナーからの読み取りまたはに書き込まれる blob が含まれています。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="pathPattern">Blob パスのパターン。 正規表現ではありません。 決定するかどうかが含まれるジョブに入力または出力として、名前を照合する blob に対してパターンを表します。 Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input または https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output より詳細な説明と例についてを参照してください。</param>
        <param name="dateFormat">日付形式です。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。</param>
        <param name="timeFormat">時刻の形式。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。</param>
        <summary>
            BlobDataSourceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または関連付けられたストレージ アカウント内のコンテナーの名前を設定します。 このコンテナーからの読み取りまたはに書き込まれる blob が含まれています。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または日付の書式を設定します。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPattern">
      <MemberSignature Language="C#" Value="public string PathPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob パス パターンを設定します。 正規表現ではありません。 決定するかどうかが含まれるジョブに入力または出力として、名前を照合する blob に対してパターンを表します。 Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input または https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output より詳細な説明と例についてを参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 1 つまたは複数の Azure ストレージ アカウントの一覧を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時刻の形式を設定します。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>