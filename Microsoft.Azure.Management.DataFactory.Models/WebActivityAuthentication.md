<Type Name="WebActivityAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication">
  <TypeSignature Language="C#" Value="public class WebActivityAuthentication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebActivityAuthentication extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebActivityAuthentication" />
  <TypeSignature Language="F#" Value="type WebActivityAuthentication = class" />
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
            Web のアクティビティの認証プロパティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivityAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.#ctor" />
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
            WebActivityAuthentication クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivityAuthentication (string type, Microsoft.Azure.Management.DataFactory.Models.SecureString pfx = null, string username = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, class Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, string username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.String,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As String, Optional pfx As SecureString = null, Optional username As String = null, Optional password As SecureString = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication : string * Microsoft.Azure.Management.DataFactory.Models.SecureString * string * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication (type, pfx, username, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="pfx" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="type">Web アクティビティ認証 (Basic/ClientCertificate)</param>
        <param name="pfx">PFX ファイルの Base64 でエンコードされた内容。</param>
        <param name="username">基本認証用 web アクティビティ認証ユーザー名。</param>
        <param name="password">PFX ファイルまたは基本認証のパスワードです。</param>
        <summary>
            WebActivityAuthentication クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または PFX ファイルまたは基本認証のパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pfx">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Pfx" />
      <MemberSignature Language="VB.NET" Value="Public Property Pfx As SecureString" />
      <MemberSignature Language="F#" Value="member this.Pfx : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Pfx" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfx")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または PFX ファイルの base64 でエンコードされた内容を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 web アクティビティ認証 (Basic/ClientCertificate)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または基本認証の web アクティビティ認証ユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="webActivityAuthentication.Validate " />
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