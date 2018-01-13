<Type Name="ErrorResponse" FullName="Microsoft.Azure.Management.DataFactory.Models.ErrorResponse">
  <TypeSignature Language="C#" Value="public class ErrorResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponse" />
  <TypeSignature Language="F#" Value="type ErrorResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Data Factory 応答の構造を定義するオブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.#ctor" />
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
            ErrorResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse (string code, string message, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ErrorResponse})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional target As String = null, Optional details As IList(Of ErrorResponse) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ErrorResponse : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ErrorResponse" Usage="new Microsoft.Azure.Management.DataFactory.Models.ErrorResponse (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt;" />
      </Parameters>
      <Docs>
        <param name="code">エラー コード。</param>
        <param name="message">エラー メッセージ。</param>
        <param name="target">プロパティ名/エラーに関連付けられている要求のパスです。</param>
        <param name="details">追加のエラーの詳細を含む配列。</param>
        <summary>
            ErrorResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            取得またはエラー コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of ErrorResponse)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ErrorResponse&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加のエラーの詳細を含む配列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            取得またはエラー メッセージを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラーに関連付けられている要求のプロパティの名前とパスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ErrorResponse.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="errorResponse.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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