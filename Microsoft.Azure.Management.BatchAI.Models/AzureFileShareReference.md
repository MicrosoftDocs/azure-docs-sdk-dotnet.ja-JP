<Type Name="AzureFileShareReference" FullName="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference">
  <TypeSignature Language="C#" Value="public class AzureFileShareReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureFileShareReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureFileShareReference" />
  <TypeSignature Language="F#" Value="type AzureFileShareReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスターにマウントする Azure のファイル共有の詳細です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureFileShareReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureFileShareReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureFileShareReference (string accountName, string azureFileUrl, Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string fileMode = null, string directoryMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string azureFileUrl, class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string fileMode, string directoryMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, azureFileUrl As String, credentials As AzureStorageCredentialsInfo, relativeMountPath As String, Optional fileMode As String = null, Optional directoryMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference : string * string * Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo * string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference (accountName, azureFileUrl, credentials, relativeMountPath, fileMode, directoryMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="azureFileUrl" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" />
        <Parameter Name="relativeMountPath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
        <Parameter Name="directoryMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">ストレージ アカウントの名前です。</param>
        <param name="azureFileUrl">Azure ファイルにアクセスする URL です。</param>
        <param name="credentials">Azure ファイルの資格情報の情報です。</param>
        <param name="relativeMountPath">Azure のファイル共有をマウントするコンピューティング ノード上の相対パスを指定します。</param>
        <param name="fileMode">ファイル モードを指定します。</param>
        <param name="directoryMode">ディレクトリのモードを指定します。</param>
        <summary>
            AzureFileShareReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストレージ アカウントの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureFileUrl">
      <MemberSignature Language="C#" Value="public string AzureFileUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureFileUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.AzureFileUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureFileUrl As String" />
      <MemberSignature Language="F#" Value="member this.AzureFileUrl : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.AzureFileUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureFileUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure のファイルにアクセスする URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As AzureStorageCredentialsInfo" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure のファイルの資格情報の情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DirectoryMode">
      <MemberSignature Language="C#" Value="public string DirectoryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DirectoryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.DirectoryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DirectoryMode As String" />
      <MemberSignature Language="F#" Value="member this.DirectoryMode : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.DirectoryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="directoryMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ディレクトリ モードを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 0777 です。 OS が linux である場合にのみ有効です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ファイルのモードを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 0777 です。 OS が linux である場合にのみ有効です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.RelativeMountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeMountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、Azure のファイル共有をマウントするコンピューティング ノード上の相対パスを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            $AZ_BATCHAI_MOUNT_ROOT 場所の下にあるすべてのファイル共有をマウントすることに注意してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureFileShareReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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