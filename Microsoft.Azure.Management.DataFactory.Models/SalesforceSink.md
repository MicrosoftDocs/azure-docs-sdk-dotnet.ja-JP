<Type Name="SalesforceSink" FullName="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink">
  <TypeSignature Language="C#" Value="public class SalesforceSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SalesforceSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SalesforceSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SalesforceSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コピー アクティビティ Salesforce シンクです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SalesforceSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string writeBehavior = null, object externalIdFieldName = null, object ignoreNullValues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string writeBehavior, object externalIdFieldName, object ignoreNullValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional writeBehavior As String = null, Optional externalIdFieldName As Object = null, Optional ignoreNullValues As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SalesforceSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SalesforceSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.SalesforceSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, writeBehavior, externalIdFieldName, ignoreNullValues)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="writeBehavior" Type="System.String" />
        <Parameter Name="externalIdFieldName" Type="System.Object" />
        <Parameter Name="ignoreNullValues" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="writeBatchSize">バッチ サイズを記述します。 型: 整数 (または式と resultType 整数)、最小値: 0。</param>
        <param name="writeBatchTimeout">バッチ タイムアウトを記述します。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="sinkRetryCount">再試行回数をシンクします。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sinkRetryWait">再試行の待機をシンクします。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="writeBehavior">操作の書き込み動作。
            既定値は Insert です。 使用可能な値が含まれます: 'Insert'、"Upsert"</param>
        <param name="externalIdFieldName">Upsert 操作の外部 ID フィールドの名前。 既定値は、'Id' 列です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="ignoreNullValues">中に入力データセット (を除くキー フィールド) から null 値を無視するかどうかを示すフラグは、操作を記述します。 既定値は false です。 場合に、設定は true、示し ADF は upsert/更新操作を実施する際に変更されていない対象オブジェクトに、データを残します ADF ではなく、挿入操作を行うデータが更新先のオブジェクトで NULL に upsert を実施する際に定義された既定値を挿入/更新操作と挿入操作を実施する際に、NULL 値を挿入します。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            SalesforceSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExternalIdFieldName">
      <MemberSignature Language="C#" Value="public object ExternalIdFieldName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ExternalIdFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.ExternalIdFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExternalIdFieldName As Object" />
      <MemberSignature Language="F#" Value="member this.ExternalIdFieldName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.ExternalIdFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="externalIdFieldName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または upsert 操作の外部の ID フィールドの名前を設定します。 既定値は、'Id' 列です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreNullValues">
      <MemberSignature Language="C#" Value="public object IgnoreNullValues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object IgnoreNullValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.IgnoreNullValues" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreNullValues As Object" />
      <MemberSignature Language="F#" Value="member this.IgnoreNullValues : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.IgnoreNullValues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreNullValues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または書き込み操作中に入力データセット (を除くキー フィールド) から null 値を無視するかどうかを示すフラグを設定します。 既定値は false です。 場合に、設定は true、示し ADF は upsert/更新操作を実施する際に変更されていない対象オブジェクトに、データを残します ADF ではなく、挿入操作を行うデータが更新先のオブジェクトで NULL に upsert を実施する際に定義された既定値を挿入/更新操作と挿入操作を実施する際に、NULL 値を挿入します。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteBehavior">
      <MemberSignature Language="C#" Value="public string WriteBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WriteBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.WriteBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteBehavior As String" />
      <MemberSignature Language="F#" Value="member this.WriteBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.WriteBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または書き込みの操作の動作を設定します。 既定値は Insert です。 使用可能な値が含まれます: 'Insert'、"Upsert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>