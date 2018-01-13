<Type Name="BlobStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class BlobStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type BlobStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/Blob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ストリーム データを含む blob 入力データ ソースについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BlobStreamInputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null, Nullable&lt;int&gt; sourcePartitionCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat, valuetype System.Nullable`1&lt;int32&gt; sourcePartitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null, Optional sourcePartitionCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource (storageAccounts, container, pathPattern, dateFormat, timeFormat, sourcePartitionCount)" />
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
        <Parameter Name="sourcePartitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccounts">1 つまたは複数の Azure ストレージ アカウントの一覧。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="container">関連付けられたストレージ アカウント内のコンテナーの名前。 このコンテナーからの読み取りまたはに書き込まれる blob が含まれています。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="pathPattern">Blob パスのパターン。 正規表現ではありません。 決定するかどうかが含まれるジョブに入力または出力として、名前を照合する blob に対してパターンを表します。 Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input または https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output より詳細な説明と例についてを参照してください。</param>
        <param name="dateFormat">日付形式です。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。</param>
        <param name="timeFormat">時刻の形式。 PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。</param>
        <param name="sourcePartitionCount">Blob の入力データ ソースのパーティション数。 1 ~ 256 の範囲です。</param>
        <summary>
            BlobStreamInputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.container")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathPattern")</AttributeName>
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
    <Member MemberName="SourcePartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SourcePartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SourcePartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SourcePartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePartitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob の入力データ ソースのパーティションの数を設定します。
            1 ~ 256 の範囲です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
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