<Type Name="SapCloudForCustomerSink" FullName="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink">
  <TypeSignature Language="C#" Value="public class SapCloudForCustomerSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SapCloudForCustomerSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SapCloudForCustomerSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SapCloudForCustomerSink = class&#xA;    inherit CopySink" />
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
            顧客シンクのコピー アクティビティ SAP クラウド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SapCloudForCustomerSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string writeBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string writeBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional writeBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, writeBehavior)" />
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
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="writeBatchSize">バッチ サイズを記述します。 型: 整数 (または式と resultType 整数)、最小値: 0。</param>
        <param name="writeBatchTimeout">バッチ タイムアウトを記述します。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="sinkRetryCount">再試行回数をシンクします。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sinkRetryWait">再試行の待機をシンクします。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="writeBehavior">操作の書き込み動作。
            既定値は、'Insert' です。 使用可能な値が含まれます: 'Insert'、'Update'</param>
        <summary>
            SapCloudForCustomerSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteBehavior">
      <MemberSignature Language="C#" Value="public string WriteBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WriteBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink.WriteBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteBehavior As String" />
      <MemberSignature Language="F#" Value="member this.WriteBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerSink.WriteBehavior" />
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
            取得または書き込みの操作の動作を設定します。 既定値は、'Insert' です。 使用可能な値が含まれます: 'Insert'、'Update'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>