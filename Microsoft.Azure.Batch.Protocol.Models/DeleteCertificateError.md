<Type Name="DeleteCertificateError" FullName="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError">
  <TypeSignature Language="C#" Value="public class DeleteCertificateError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeleteCertificateError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" />
  <TypeSignature Language="VB.NET" Value="Public Class DeleteCertificateError" />
  <TypeSignature Language="F#" Value="type DeleteCertificateError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            証明書を削除するときに、バッチ サービスで発生したエラーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeleteCertificateError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError (string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional values As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" Usage="new Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError (code, message, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="code">証明書の削除エラーの識別子。 コードは変化せず、プログラムでの使用を目的としています。</param>
        <param name="message">ユーザー インターフェイスでの表示に適したするもので、証明書の削除エラーを説明するメッセージ。</param>
        <param name="values">証明書の削除エラーに関連する追加のエラー詳細の一覧。</param>
        <summary>
            DeleteCertificateError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の削除エラーの識別子を設定します。
            コードは変化せず、プログラムでの使用を目的としています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するユーザー インターフェイスでの表示に適したもので、証明書の削除エラーを説明するメッセージ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の削除エラーに関連する追加のエラー詳細の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この一覧には、アクティブなプールこの証明書を参照しているノードなどの詳細が含まれています。 ただし、大量のリソースは、証明書を参照する場合は、最初の 100 についてのみ説明の一覧が含まれます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>