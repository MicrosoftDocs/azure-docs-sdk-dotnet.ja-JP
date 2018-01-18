<Type Name="DataPackage" FullName="System.Fabric.DataPackage">
  <TypeSignature Language="C#" Value="public sealed class DataPackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataPackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataPackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataPackage" />
  <TypeSignature Language="F#" Value="type DataPackage = class" />
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
      <para><span data-ttu-id="c10f5-101">このクラスは、アプリケーションにデータのパッケージを表します。</span><span class="sxs-lookup"><span data-stu-id="c10f5-101">This class represents a data package in the application.</span></span> <span data-ttu-id="c10f5-102">静的なデータの (アップグレードすることができます)。 アプリケーションによって使用される、データ パッケージで構成されます。</span><span class="sxs-lookup"><span data-stu-id="c10f5-102">A data package consists of static data (that can be upgraded) that is consumed by the application.</span></span> <span data-ttu-id="c10f5-103">詳細については、https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c10f5-103">For more information see https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.DataPackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.DataPackageDescription" Usage="System.Fabric.DataPackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c10f5-104">取得、<see cref="T:System.Fabric.Description.PackageDescription" />オブジェクトに関連付けられている、<see cref="T:System.Fabric.DataPackage" />です。</span><span class="sxs-lookup"><span data-stu-id="c10f5-104">Gets the <see cref="T:System.Fabric.Description.PackageDescription" /> object associated with the <see cref="T:System.Fabric.DataPackage" />.</span></span> <span data-ttu-id="c10f5-105">パッケージの説明は、名など、このパッケージに関する追加情報にアクセスするために使用できますのバージョンなどです。</span><span class="sxs-lookup"><span data-stu-id="c10f5-105">The package description can be used to access additional information about this package such as the name, version etc.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="c10f5-106"><see cref="T:System.Fabric.Description.PackageDescription" /> に関連付けられている <see cref="T:System.Fabric.DataPackage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c10f5-106">The <see cref="T:System.Fabric.Description.PackageDescription" /> object associated with the <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.DataPackage.Path" />
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
          <para><span data-ttu-id="c10f5-107">ローカル パスを取得<see cref="T:System.Fabric.DataPackage" />です。</span><span class="sxs-lookup"><span data-stu-id="c10f5-107">Gets the local path of <see cref="T:System.Fabric.DataPackage" />.</span></span> <span data-ttu-id="c10f5-108">このパスには、データ パッケージの内容が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c10f5-108">This path contains the contents of the data package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c10f5-109">ローカル パス<see cref="T:System.Fabric.DataPackage" />です。</span><span class="sxs-lookup"><span data-stu-id="c10f5-109">The local path of <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>