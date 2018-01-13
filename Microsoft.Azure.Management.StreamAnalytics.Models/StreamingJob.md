<Type Name="StreamingJob" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob">
  <TypeSignature Language="C#" Value="public class StreamingJob : Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StreamingJob extends Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamingJob&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StreamingJob = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Streamng ジョブ オブジェクトを名前付きのストリーミング ジョブに関連付けられているすべての情報を格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StreamingJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku = null, string jobId = null, string provisioningState = null, string jobState = null, string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null, Nullable&lt;DateTime&gt; lastOutputEventTime = null, string eventsOutOfOrderPolicy = null, string outputErrorPolicy = null, Nullable&lt;int&gt; eventsOutOfOrderMaxDelayInSeconds = null, Nullable&lt;int&gt; eventsLateArrivalMaxDelayInSeconds = null, string dataLocale = null, string compatibilityLevel = null, Nullable&lt;DateTime&gt; createdDate = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs = null, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku, string jobId, string provisioningState, string jobState, string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastOutputEventTime, string eventsOutOfOrderPolicy, string outputErrorPolicy, valuetype System.Nullable`1&lt;int32&gt; eventsOutOfOrderMaxDelayInSeconds, valuetype System.Nullable`1&lt;int32&gt; eventsLateArrivalMaxDelayInSeconds, string dataLocale, string compatibilityLevel, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdDate, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.StreamAnalytics.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Input},Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Output},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Function},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob (id, name, type, location, tags, sku, jobId, provisioningState, jobState, outputStartMode, outputStartTime, lastOutputEventTime, eventsOutOfOrderPolicy, outputErrorPolicy, eventsOutOfOrderMaxDelayInSeconds, eventsLateArrivalMaxDelayInSeconds, dataLocale, compatibilityLevel, createdDate, inputs, transformation, outputs, functions, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Sku" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="jobState" Type="System.String" />
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastOutputEventTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="eventsOutOfOrderPolicy" Type="System.String" />
        <Parameter Name="outputErrorPolicy" Type="System.String" />
        <Parameter Name="eventsOutOfOrderMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eventsLateArrivalMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dataLocale" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.String" />
        <Parameter Name="createdDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" />
        <Parameter Name="functions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="tags">リソース タグ</param>
        <param name="sku">ストリーミング ジョブの SKU をについて説明します。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="jobId">ストリーミング ジョブを一意に識別する GUID です。
            この GUID は、ストリーミング ジョブの作成時に生成されます。</param>
        <param name="provisioningState">ストリーミング ジョブのプロビジョニング状態を説明します。</param>
        <param name="jobState">ストリーミング ジョブの状態を説明します。</param>
        <param name="outputStartMode">このプロパティは、作成時に、ジョブをすぐに開始することが必要な場合にのみ使用する必要があります。 値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。 使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</param>
        <param name="outputStartTime">値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。 このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</param>
        <param name="lastOutputEventTime">値は、ストリーミング ジョブや、出力いないまだ生成されていることを示す null の最後の出力イベントの時刻を示すか、ISO 8601 フォーマットされたタイムスタンプです。 複数の出力または複数のストリームでは、そのセットに最新の値を示します。</param>
        <param name="eventsOutOfOrderPolicy">入力イベント ストリームで順序どおりに到着したイベントに適用するポリシーを示します。
            使用可能な値が含まれます: '調整'、'Drop'</param>
        <param name="outputErrorPolicy">出力に送られてくるし、外部ストレージことによって形式が正しくありません (不足している列の値、無効な型やサイズの列の値) に書き込むことはできませんをイベントに適用するポリシーを示します。 使用可能な値が含まれます: 'Stop'、'Drop'</param>
        <param name="eventsOutOfOrderMaxDelayInSeconds">順序不定なイベントを調整する順序に戻ります、秒単位で許容できる最大遅延。</param>
        <param name="eventsLateArrivalMaxDelayInSeconds">遅れて到着するイベントが含まれるなります秒単位で最大の遅延時間を許容できます。  サポートされている範囲は-1 1814399 (20.23:59:59 日) を指定し、-1 を使用して、無期限に待機を指定します。 プロパティがない場合は-1 の値が解釈されます。</param>
        <param name="dataLocale">Stream analytics ジョブのデータのロケールです。 値がセット https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. からサポートされている .NET カルチャの名前を指定する必要があります。
            指定しない場合は、' EN-US ' に既定値です。</param>
        <param name="compatibilityLevel">ストリーミング ジョブの特定のランタイム動作を制御します。 使用可能な値が含まれます: '1.0'</param>
        <param name="createdDate">値は、ISO 8601 形式のストリーミング ジョブが作成されたことを示す UTC タイムスタンプです。</param>
        <param name="inputs">ストリーミング ジョブに対する 1 つまたは複数の入力の一覧。 PUT 要求でこのプロパティを指定する場合、各入力の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の入力の修正プログラムを適用して利用できる API を使用する必要があります。</param>
        <param name="transformation">クエリと、ストリーミング ジョブに使用するストリーミング ユニットの数を示します。 PUT 要求でこのプロパティを指定する場合、変換の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。
            個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</param>
        <param name="outputs">ストリーミング ジョブの 1 つまたは複数の出力の一覧です。 PUT 要求でこのプロパティを指定する場合、各出力の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の出力の修正プログラムを適用して利用できる API を使用する必要があります。</param>
        <param name="functions">ストリーミング ジョブの 1 つまたは複数の関数の一覧です。 PUT 要求でこのプロパティを指定する場合、各関数は、name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</param>
        <param name="etag">ストリーミング ジョブの現在のエンティティ タグ。
            これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</param>
        <summary>
            StreamingJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public string CompatibilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property CompatibilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.compatibilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコントロールのストリーミング ジョブの特定のランタイム動作を設定します。 使用可能な値が含まれます: '1.0'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            値を取得は、ISO 8601 形式のストリーミング ジョブが作成されたことを示す UTC タイムスタンプです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLocale">
      <MemberSignature Language="C#" Value="public string DataLocale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataLocale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLocale As String" />
      <MemberSignature Language="F#" Value="member this.DataLocale : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLocale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または stream analytics ジョブのデータのロケールを設定します。 値がセット https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. からサポートされている .NET カルチャの名前を指定する必要があります。
            指定しない場合は、' EN-US ' に既定値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストリーミング ジョブの現在のエンティティ タグを取得します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsLateArrivalMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsLateArrivalMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsLateArrivalMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsLateArrivalMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsLateArrivalMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または遅延到着したイベントが含まれるなります許容量の最大遅延時間を秒単位で設定します。  サポートされている範囲は-1 1814399 (20.23:59:59 日) を指定し、-1 を使用して、無期限に待機を指定します。 プロパティがない場合は-1 の値が解釈されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsOutOfOrderMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはする順序に戻りますを順序不定なイベントを調整できる最大許容遅延時間を秒単位で設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderPolicy">
      <MemberSignature Language="C#" Value="public string EventsOutOfOrderPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventsOutOfOrderPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderPolicy As String" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、入力イベント ストリームで順序どおりに到着したイベントに適用するポリシーを示します。 使用可能な値が含まれます: '調整'、'Drop'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberSignature Language="VB.NET" Value="Public Property Functions As IList(Of Function)" />
      <MemberSignature Language="F#" Value="member this.Functions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.functions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストリーミング ジョブの 1 つまたは複数の関数の一覧を設定します。
            PUT 要求でこのプロパティを指定する場合、各関数は、name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of Input)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストリーミング ジョブに対する 1 つまたは複数の入力の一覧を設定します。 PUT 要求でこのプロパティを指定する場合、各入力の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の入力の修正プログラムを適用して利用できる API を使用する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストリーミング ジョブを一意に識別する GUID を取得します。 この GUID は、ストリーミング ジョブの作成時に生成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobState">
      <MemberSignature Language="C#" Value="public string JobState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobState As String" />
      <MemberSignature Language="F#" Value="member this.JobState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、ストリーミング ジョブの状態について説明します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOutputEventTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastOutputEventTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastOutputEventTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOutputEventTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastOutputEventTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastOutputEventTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            値を取得は、ストリーミング ジョブや、出力いないまだ生成されていることを示す null の最後の出力イベントの時刻を示すか、ISO 8601 フォーマットされたタイムスタンプです。 複数の出力または複数のストリームでは、そのセットに最新の値を示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputErrorPolicy">
      <MemberSignature Language="C#" Value="public string OutputErrorPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputErrorPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputErrorPolicy As String" />
      <MemberSignature Language="F#" Value="member this.OutputErrorPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputErrorPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、出力に送られてくるし、外部ストレージことによって形式が正しくありません (不足している列の値、無効な型やサイズの列の値) に書き込むことはできませんをイベントに適用するポリシーを示します。 使用可能な値が含まれます: 'Stop'、'Drop'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of Output)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストリーミング ジョブの 1 つまたは複数の出力の一覧を設定します。
            PUT 要求でこのプロパティを指定する場合、各出力の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の出力の修正プログラムを適用して利用できる API を使用する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定がこのプロパティは、作成時に、ジョブをすぐに開始することが必要な場合にのみ使用する必要があります。 値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。 使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。 このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、ストリーミング ジョブのプロビジョニング状態について説明します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.StreamAnalytics.Models.Sku with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ストリーミング ジョブの SKU をについて説明します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberSignature Language="VB.NET" Value="Public Property Transformation As Transformation" />
      <MemberSignature Language="F#" Value="member this.Transformation : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、クエリと、ストリーミング ジョブに使用するストリーミング ユニットの数を示します。 PUT 要求でこのプロパティを指定する場合、変換の name プロパティが必要です。 PATCH 操作では、このプロパティを変更できません。 個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>