<Type Name="HttpSource" FullName="Microsoft.Azure.Management.DataFactory.Models.HttpSource">
  <TypeSignature Language="C#" Value="public class HttpSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HttpSource" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type HttpSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            HTTP ファイルのコピー活動元。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            HttpSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object httpRequestTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object httpRequestTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional httpRequestTimeout As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HttpSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HttpSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.HttpSource (additionalProperties, sourceRetryCount, sourceRetryWait, httpRequestTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="httpRequestTimeout" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="httpRequestTimeout">HTTP サーバーからの HTTP 応答を取得する HTTP クライアントのタイムアウトを指定します。 既定値は System.Net.HttpWebRequest.Timeout に相当します。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <summary>
            HttpSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpRequestTimeout">
      <MemberSignature Language="C#" Value="public object HttpRequestTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpRequestTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpSource.HttpRequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpRequestTimeout As Object" />
      <MemberSignature Language="F#" Value="member this.HttpRequestTimeout : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpSource.HttpRequestTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpRequestTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HTTP サーバーからの HTTP 応答を取得する HTTP クライアントのタイムアウトを指定します。 既定値は System.Net.HttpWebRequest.Timeout に相当します。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>