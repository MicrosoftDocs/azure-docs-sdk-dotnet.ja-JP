<Type Name="PackageSharingPolicy" FullName="System.Fabric.PackageSharingPolicy">
  <TypeSignature Language="C#" Value="public class PackageSharingPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PackageSharingPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageSharingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class PackageSharingPolicy" />
  <TypeSignature Language="F#" Value="type PackageSharingPolicy = class" />
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
      <para><span data-ttu-id="e3122-101">パッケージを共有するためのポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="e3122-101">Represents a policy for the package sharing.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageSharingPolicy (string packageName, System.Fabric.PackageSharingPolicyScope sharingScope);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageName, valuetype System.Fabric.PackageSharingPolicyScope sharingScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageSharingPolicy.#ctor(System.String,System.Fabric.PackageSharingPolicyScope)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (packageName As String, sharingScope As PackageSharingPolicyScope)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PackageSharingPolicy : string * System.Fabric.PackageSharingPolicyScope -&gt; System.Fabric.PackageSharingPolicy" Usage="new System.Fabric.PackageSharingPolicy (packageName, sharingScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
        <Parameter Name="sharingScope" Type="System.Fabric.PackageSharingPolicyScope" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para><span data-ttu-id="e3122-102">共有する必要がある特定のパッケージの名前です。</span><span class="sxs-lookup"><span data-stu-id="e3122-102">Name of specific package that should be shared.</span></span> </para>
        </param>
        <param name="sharingScope">
          <para><span data-ttu-id="e3122-103">コード、構成、データまたはすべてのパッケージを共有する必要があるかどうかを示すために PackageSharingPolicyScope パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e3122-103">PackageSharingPolicyScope parameter to indicate whether Code, Config, Data or All packages should be shared.</span></span> </para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="e3122-104">PackageSharingPolicy オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="e3122-104">Creates PackageSharingPolicy object.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageName">
      <MemberSignature Language="C#" Value="public string PackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageSharingPolicy.PackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PackageName As String" />
      <MemberSignature Language="F#" Value="member this.PackageName : string" Usage="System.Fabric.PackageSharingPolicy.PackageName" />
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
          <para><span data-ttu-id="e3122-105">コード、構成、または共有すべきデータ パッケージの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e3122-105">Gets the name of code, configuration or data package that should be shared.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e3122-106">共有する必要があるコード、構成またはデータのパッケージの名前です。</span><span class="sxs-lookup"><span data-stu-id="e3122-106">The name of code, configuration or data package that should be shared.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharingScope">
      <MemberSignature Language="C#" Value="public System.Fabric.PackageSharingPolicyScope SharingScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PackageSharingPolicyScope SharingScope" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageSharingPolicy.SharingScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharingScope As PackageSharingPolicyScope" />
      <MemberSignature Language="F#" Value="member this.SharingScope : System.Fabric.PackageSharingPolicyScope" Usage="System.Fabric.PackageSharingPolicy.SharingScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PackageSharingPolicyScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e3122-107">パッケージの共有ポリシーのスコープを取得します。</span><span class="sxs-lookup"><span data-stu-id="e3122-107">Gets the scope for package sharing policy.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e3122-108">パッケージの共有ポリシーのスコープです。</span><span class="sxs-lookup"><span data-stu-id="e3122-108">The scope for package sharing policy.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>