<Type Name="MountSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.MountSettings">
  <TypeSignature Language="C#" Value="public class MountSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MountSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.MountSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MountSettings" />
  <TypeSignature Language="F#" Value="type MountSettings = class" />
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
            ファイル サーバーの詳細です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MountSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.MountSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MountSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MountSettings (string mountPoint = null, string fileServerPublicIP = null, string fileServerInternalIP = null, string fileServerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mountPoint, string fileServerPublicIP, string fileServerInternalIP, string fileServerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.MountSettings.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional mountPoint As String = null, Optional fileServerPublicIP As String = null, Optional fileServerInternalIP As String = null, Optional fileServerType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.MountSettings : string * string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.MountSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.MountSettings (mountPoint, fileServerPublicIP, fileServerInternalIP, fileServerType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mountPoint" Type="System.String" />
        <Parameter Name="fileServerPublicIP" Type="System.String" />
        <Parameter Name="fileServerInternalIP" Type="System.String" />
        <Parameter Name="fileServerType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mountPoint">NFS がサーバーにマウントされているパスです。</param>
        <param name="fileServerPublicIP">ファイル サーバー VM のパブリック IP はします。</param>
        <param name="fileServerInternalIP">サブネット内にあるファイルからサーバーにアクセスするために使用する内部サブネット IP です。</param>
        <param name="fileServerType">Fileserver nfs などの種類、glusterfs などです。</param>
        <summary>
            MountSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServerInternalIP">
      <MemberSignature Language="C#" Value="public string FileServerInternalIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileServerInternalIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerInternalIP" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServerInternalIP As String" />
      <MemberSignature Language="F#" Value="member this.FileServerInternalIP : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerInternalIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServerInternalIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブネット内にあるファイルからサーバーにアクセスするために使用する内部サブネット IP を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServerPublicIP">
      <MemberSignature Language="C#" Value="public string FileServerPublicIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileServerPublicIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerPublicIP" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServerPublicIP As String" />
      <MemberSignature Language="F#" Value="member this.FileServerPublicIP : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerPublicIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServerPublicIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル サーバー VM のパブリック IP を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServerType">
      <MemberSignature Language="C#" Value="public string FileServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServerType As String" />
      <MemberSignature Language="F#" Value="member this.FileServerType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountSettings.FileServerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Nfs など、ファイル サーバーの種類の設定を取得または glusterfs などです。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'nfs'、'glusterfs'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MountPoint">
      <MemberSignature Language="C#" Value="public string MountPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountSettings.MountPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MountPoint As String" />
      <MemberSignature Language="F#" Value="member this.MountPoint : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountSettings.MountPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または NFS がサーバーにマウントされているパスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>