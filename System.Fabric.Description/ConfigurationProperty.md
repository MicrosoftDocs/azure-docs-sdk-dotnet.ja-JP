<Type Name="ConfigurationProperty" FullName="System.Fabric.Description.ConfigurationProperty">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationProperty extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationProperty" />
  <TypeSignature Language="F#" Value="type ConfigurationProperty = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="3c6be-101">構成設定と、サービスまたはアプリケーション構成に使用できる値を指定します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-101">Specifies a configuration setting and its value that can be used to configure a service or application.</span></span></para>
      <para><span data-ttu-id="3c6be-102">設定は、サービス マニフェスト内の settings.xml ファイルに指定します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-102">The settings are specified in the settings.xml file in the service manifest.</span></span> <span data-ttu-id="3c6be-103">詳細については、https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3c6be-103">For more information see https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public System.Security.SecureString DecryptValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.SecureString DecryptValue() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationProperty.DecryptValue" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptValue () As SecureString" />
      <MemberSignature Language="F#" Value="member this.DecryptValue : unit -&gt; System.Security.SecureString" Usage="configurationProperty.DecryptValue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="3c6be-104">暗号化された値を復号化し、SecureString として返します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-104">Decrypts an encrypted value and returns it as a SecureString.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3c6be-105"><see cref="T:System.Security.SecureString" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-105">Returns <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks><span data-ttu-id="3c6be-106">Https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management メソッドを使用してこの値は実行時の暗号化を解除する方法と、シークレットを暗号化し、構成に格納する方法の例についてを参照してください。</span><span class="sxs-lookup"><span data-stu-id="3c6be-106">See https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management for an example on how to encrypt a secret and store it in the configuration and how to use this method to decrypt the value at runtime.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException">
          <para><span data-ttu-id="3c6be-107">値、<see cref="T:System.Fabric.Description.ConfigurationProperty" />は暗号化されません。</span><span class="sxs-lookup"><span data-stu-id="3c6be-107">The value of the <see cref="T:System.Fabric.Description.ConfigurationProperty" /> is not encrypted.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="IsEncrypted">
      <MemberSignature Language="C#" Value="public bool IsEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEncrypted" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEncrypted : bool" Usage="System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3c6be-108">構成が暗号化されているかどうかを示すフラグを取得します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-108">Gets a flag indicating whether the configuration is encrypted.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="3c6be-109">構成が暗号化されている; 場合、true を返しますfalse の場合、それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="3c6be-109">Returns true if the configuration is encrypted; false, otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MustOverride">
      <MemberSignature Language="C#" Value="public bool MustOverride { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MustOverride" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MustOverride As Boolean" />
      <MemberSignature Language="F#" Value="member this.MustOverride : bool" Usage="System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3c6be-110">アプリケーション マニフェストに、設定をオーバーライドする必要があるかどうかを示すフラグを取得します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-110">Gets a flag indicating whether the setting must be overridden in the application manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c6be-111">アプリケーション マニフェストに、設定をオーバーライドする必要があるかどうかを示すフラグします。</span><span class="sxs-lookup"><span data-stu-id="3c6be-111">Flag indicating whether the setting must be overridden in the application manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.ConfigurationProperty.Name" />
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
          <para><span data-ttu-id="3c6be-112">サービス マニフェスト内の settings.xml ファイルに指定された設定の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-112">Gets the name of the setting as specified in the settings.xml file in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c6be-113">設定の名前。</span><span class="sxs-lookup"><span data-stu-id="3c6be-113">The name of the setting.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="System.Fabric.Description.ConfigurationProperty.Value" />
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
          <para><span data-ttu-id="3c6be-114">設定の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="3c6be-114">Gets the value of the setting.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c6be-115">設定の値です。</span><span class="sxs-lookup"><span data-stu-id="3c6be-115">The value of the setting.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>