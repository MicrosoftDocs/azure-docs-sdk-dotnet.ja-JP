<Type Name="ErrorDetails" FullName="Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails">
  <TypeSignature Language="C#" Value="public class ErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorDetails" />
  <TypeSignature Language="F#" Value="type ErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Store エラーの詳細情報
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ErrorDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetails (string code = null, string message = null, string target = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional target As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails : string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails (code, message, target)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="code">HTTP ステータス コードまたはこのエラーに関連付けられているエラー コード</param>
        <param name="message">エラー メッセージに基づいてブラウザーの言語のローカライズ</param>
        <param name="target">特定のエラー (たとえば、エラー プロパティの名前) のターゲットです。</param>
        <summary>
            ErrorDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            HTTP ステータス コードまたはこのエラーに関連付けられているエラー コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            ブラウザーの言語に基づいて、エラー メッセージがローカライズされた取得
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Target" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ErrorDetails.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            特定のエラー (たとえば、エラー プロパティの名前) のターゲットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>