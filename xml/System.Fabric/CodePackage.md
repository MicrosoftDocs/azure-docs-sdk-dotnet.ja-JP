<Type Name="CodePackage" FullName="System.Fabric.CodePackage">
  <TypeSignature Language="C#" Value="public sealed class CodePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CodePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CodePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CodePackage" />
  <TypeSignature Language="F#" Value="type CodePackage = class" />
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
      <para><span data-ttu-id="e4e7f-101">コード パッケージ定義を表します。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-101">Represents the code package definition.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.CodePackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.CodePackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As CodePackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.CodePackageDescription" Usage="System.Fabric.CodePackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.CodePackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e4e7f-102"><see cref="T:System.Fabric.Description.CodePackageDescription" /> の <see cref="T:System.Fabric.CodePackage" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-102">Gets the <see cref="T:System.Fabric.Description.CodePackageDescription" /> for the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e4e7f-103"><see cref="T:System.Fabric.CodePackage" /> の <see cref="T:System.Fabric.Description.CodePackageDescription" />。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-103">The <see cref="T:System.Fabric.Description.CodePackageDescription" /> for the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryPointRunAsPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.RunAsPolicyDescription EntryPointRunAsPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.RunAsPolicyDescription EntryPointRunAsPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.EntryPointRunAsPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryPointRunAsPolicy As RunAsPolicyDescription" />
      <MemberSignature Language="F#" Value="member this.EntryPointRunAsPolicy : System.Fabric.Description.RunAsPolicyDescription" Usage="System.Fabric.CodePackage.EntryPointRunAsPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.RunAsPolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e4e7f-104">取得、<see cref="T:System.Fabric.Description.RunAsPolicyDescription" />のメイン エントリ ポイントに関連付けられている、<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-104">Gets the <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> associated with Main EntryPoint in the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e4e7f-105"><see cref="T:System.Fabric.Description.RunAsPolicyDescription" />のメイン エントリ ポイントに関連付けられている、<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-105">The <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> associated with Main EntryPoint in the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.CodePackage.Path" />
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
          <para><span data-ttu-id="e4e7f-106">パスを取得、<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-106">Gets the path to the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e4e7f-107">パス、<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-107">The path to the <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupEntryPointRunAsPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.RunAsPolicyDescription SetupEntryPointRunAsPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.RunAsPolicyDescription SetupEntryPointRunAsPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.SetupEntryPointRunAsPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SetupEntryPointRunAsPolicy As RunAsPolicyDescription" />
      <MemberSignature Language="F#" Value="member this.SetupEntryPointRunAsPolicy : System.Fabric.Description.RunAsPolicyDescription" Usage="System.Fabric.CodePackage.SetupEntryPointRunAsPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.RunAsPolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e4e7f-108">取得、<see cref="T:System.Fabric.Description.RunAsPolicyDescription" />にセットアップ エントリ ポイントに関連付けられたオブジェクト<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-108">Gets the <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> object associated with Setup EntryPoint in <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e4e7f-109"><see cref="T:System.Fabric.Description.RunAsPolicyDescription" />にセットアップ エントリ ポイントに関連付けられたオブジェクト<see cref="T:System.Fabric.CodePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="e4e7f-109">The <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> object associated with Setup EntryPoint in <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>