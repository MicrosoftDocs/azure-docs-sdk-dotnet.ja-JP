<Type Name="ClientScriptForConnect" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect">
  <TypeSignature Language="C#" Value="public class ClientScriptForConnect" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientScriptForConnect extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientScriptForConnect" />
  <TypeSignature Language="F#" Value="type ClientScriptForConnect = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアント スクリプト ファイルの詳細/フォルダーを復元します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClientScriptForConnect クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect (string scriptContent = null, string scriptExtension = null, string osType = null, string url = null, string scriptNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scriptContent, string scriptExtension, string osType, string url, string scriptNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scriptContent As String = null, Optional scriptExtension As String = null, Optional osType As String = null, Optional url As String = null, Optional scriptNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect (scriptContent, scriptExtension, osType, url, scriptNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scriptContent" Type="System.String" />
        <Parameter Name="scriptExtension" Type="System.String" />
        <Parameter Name="osType" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="scriptNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scriptContent">ファイル用のクライアント スクリプトの内容をファイル/フォルダーを復元します。</param>
        <param name="scriptExtension">ファイル用のクライアント スクリプトの拡張機能のファイル/フォルダーの復元 - .ps1 .sh などです。</param>
        <param name="osType">OS の種類 - Windows、Linux など対象のファイル/フォルダーの復元のクライアント スクリプトの動作です。</param>
        <param name="url">URL の実行可能ファイル コンテンツのソースの場所から。 これが null でない場合、ScriptContent は適していません。</param>
        <param name="scriptNameSuffix">ユーザーにダウンロードしたスクリプトの名前に追加する必要があります必須サフィックスです。
            場合は、null または空し、それを無視します。</param>
        <summary>
            ClientScriptForConnect クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の OS の種類 - Windows、Linux など対象のファイル/フォルダーの復元のクライアント スクリプトの動作です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptContent">
      <MemberSignature Language="C#" Value="public string ScriptContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptContent As String" />
      <MemberSignature Language="F#" Value="member this.ScriptContent : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル用のクライアント スクリプトのファイルの内容を設定/フォルダーを復元します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptExtension">
      <MemberSignature Language="C#" Value="public string ScriptExtension { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptExtension" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptExtension As String" />
      <MemberSignature Language="F#" Value="member this.ScriptExtension : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptExtension")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定ファイル用のクライアント スクリプトのファイル拡張子とフォルダーの復元 - .ps1 .sh などです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptNameSuffix">
      <MemberSignature Language="C#" Value="public string ScriptNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.ScriptNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはダウンロードするユーザーが指定されたスクリプトの名前に追加する必要があります必須サフィックスを設定します。
            場合は、null または空し、それを無視します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテンツのソースの場所から実行可能ファイルの URL を設定します。 これが null でない場合、ScriptContent は適していません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>