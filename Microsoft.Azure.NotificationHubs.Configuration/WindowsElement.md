<Type Name="WindowsElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement">
  <TypeSignature Language="C#" Value="public class WindowsElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WindowsElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Service bus の構成が windows 要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.Azure.NotificationHubs.Configuration.WindowsElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.Azure.NotificationHubs.Configuration.WindowsElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.CopyFrom(Microsoft.Azure.NotificationHubs.Configuration.WindowsElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As WindowsElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.Azure.NotificationHubs.Configuration.WindowsElement -&gt; unit" Usage="windowsElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement" />
      </Parameters>
      <Docs>
        <param name="source">Windows 要素をコピーします。</param>
        <summary>現在のインスタンスに指定されたウィンドウの要素をコピーします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domain">
      <MemberSignature Language="C#" Value="public string Domain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Domain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Domain" />
      <MemberSignature Language="VB.NET" Value="Public Property Domain As String" />
      <MemberSignature Language="F#" Value="member this.Domain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Domain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("domain", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはドメインを設定します。</summary>
        <value>ドメイン。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("password", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>パスワードを取得または設定します。</summary>
        <value>パスワード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定のプロパティのコレクションを設定します。</summary>
        <value>構成プロパティのコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsUris">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection StsUris { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection StsUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.StsUris" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property StsUris As StsUriElementCollection" />
      <MemberSignature Language="F#" Value="member this.StsUris : Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.StsUris" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("stsUris", IsDefaultCollection=false, IsRequired=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセキュリティ トークン サービス (STS) URI のコレクションを設定します。</summary>
        <value>セキュリティ トークン サービス (STS) URI のコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultCredentials">
      <MemberSignature Language="C#" Value="public bool UseDefaultCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultCredentials As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultCredentials : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultCredentials", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または既定の資格情報を使用するかどうかを示す値を設定します。</summary>
        <value>既定の資格情報を使用する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("userName", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはユーザー名を設定します。</summary>
        <value>ユーザー名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>