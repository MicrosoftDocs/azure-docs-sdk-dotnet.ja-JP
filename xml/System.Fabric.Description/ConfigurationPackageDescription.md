<Type Name="ConfigurationPackageDescription" FullName="System.Fabric.Description.ConfigurationPackageDescription">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationPackageDescription : System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationPackageDescription extends System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationPackageDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationPackageDescription&#xA;Inherits PackageDescription" />
  <TypeSignature Language="F#" Value="type ConfigurationPackageDescription = class&#xA;    inherit PackageDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PackageDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="72b39-101">構成パッケージをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="72b39-101">Describes a configuration package.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ConfigurationSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ConfigurationSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationPackageDescription.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As ConfigurationSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.Description.ConfigurationSettings" Usage="System.Fabric.Description.ConfigurationPackageDescription.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use Settings property of System.Fabric.ConfigurationPackage type.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ConfigurationSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="72b39-102">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="72b39-102">DEPRECATED.</span></span> <span data-ttu-id="72b39-103">構成パッケージから解析された構成設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="72b39-103">Gets the parsed configuration settings from the configuration package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="72b39-104">構成パッケージから解析された構成設定。</span><span class="sxs-lookup"><span data-stu-id="72b39-104">The parsed configuration settings from the configuration package.</span></span></para>
        </value>
        <remarks><span data-ttu-id="72b39-105">このプロパティは今後使用しません。</span><span class="sxs-lookup"><span data-stu-id="72b39-105">This property is obsolete.</span></span> <span data-ttu-id="72b39-106">代わりに System.Fabric.ConfigurationPackage 型のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="72b39-106">Use Settings property of System.Fabric.ConfigurationPackage type instead.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>