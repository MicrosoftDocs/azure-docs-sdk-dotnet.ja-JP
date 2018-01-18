<Type Name="WindowsCredentials" FullName="System.Fabric.WindowsCredentials">
  <TypeSignature Language="C#" Value="public sealed class WindowsCredentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WindowsCredentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.WindowsCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WindowsCredentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type WindowsCredentials = class&#xA;    inherit SecurityCredentials" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.SecurityCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b14b1-101">Active directory ドメインの資格情報を表します。</span><span class="sxs-lookup"><span data-stu-id="b14b1-101">Represents the active directory domain credential.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.WindowsCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b14b1-102"><see cref="T:System.Fabric.WindowsCredentials" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b14b1-102">Initializes a new instance of the <see cref="T:System.Fabric.WindowsCredentials" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.WindowsCredentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.WindowsCredentials.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b14b1-103">既定値は、通信を保護する方法を取得または、<see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />です。</span><span class="sxs-lookup"><span data-stu-id="b14b1-103">Gets or sets how communication is protected, default value is <see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b14b1-104">資格情報の保護レベル。</span><span class="sxs-lookup"><span data-stu-id="b14b1-104">The protection level of the credential.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIdentities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; RemoteIdentities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; RemoteIdentities" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.WindowsCredentials.RemoteIdentities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteIdentities As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.RemoteIdentities : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.WindowsCredentials.RemoteIdentities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b14b1-105">一覧の設定を取得またはアカウント名またはグループ名のいずれかのリモート クライアントの active directory ドメインの id、各エントリができます。</span><span class="sxs-lookup"><span data-stu-id="b14b1-105">Gets or sets the list of active directory domain identities of remote clients, each entry can be either account name or group name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b14b1-106">一覧のリモート クライアントの active directory ドメインの id を各エントリをアカウント名またはグループ名のいずれか指定できます。</span><span class="sxs-lookup"><span data-stu-id="b14b1-106">The list of active directory domain identities of remote clients, each entry can be either account name or group name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteSpn">
      <MemberSignature Language="C#" Value="public string RemoteSpn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteSpn" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.WindowsCredentials.RemoteSpn" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteSpn As String" />
      <MemberSignature Language="F#" Value="member this.RemoteSpn : string with get, set" Usage="System.Fabric.WindowsCredentials.RemoteSpn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b14b1-107">取得または設定、リモートのリスナーのサービス プリンシパル名にしておくリモート リスナーは、コンピューター アカウントとして実行する場合は空です。</span><span class="sxs-lookup"><span data-stu-id="b14b1-107">Gets or sets the service principal name of remote listener, can be left empty if the remote listener runs as machine accounts.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b14b1-108">リモートのリスナーのサービス プリンシパル名はコンピューターのアカウントと、リモートのリスナーが実行されている場合は空のままにできます。</span><span class="sxs-lookup"><span data-stu-id="b14b1-108">The service principal name of remote listener, can be left empty if the remote listener runs as machine accounts.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>