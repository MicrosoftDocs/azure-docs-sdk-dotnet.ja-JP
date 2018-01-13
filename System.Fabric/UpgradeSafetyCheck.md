<Type Name="UpgradeSafetyCheck" FullName="System.Fabric.UpgradeSafetyCheck">
  <TypeSignature Language="C#" Value="public abstract class UpgradeSafetyCheck" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit UpgradeSafetyCheck extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeSafetyCheck" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class UpgradeSafetyCheck" />
  <TypeSignature Language="F#" Value="type UpgradeSafetyCheck = class" />
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
      <para><span data-ttu-id="8a045-101">現在実行されているノードのアップグレード中に安全性チェックを表します。</span><span class="sxs-lookup"><span data-stu-id="8a045-101">Represents the safety check that is currently being performed for a node during upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal UpgradeSafetyCheck (System.Fabric.UpgradeSafetyCheckKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.UpgradeSafetyCheckKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.UpgradeSafetyCheck.#ctor(System.Fabric.UpgradeSafetyCheckKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (kind As UpgradeSafetyCheckKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.UpgradeSafetyCheck : System.Fabric.UpgradeSafetyCheckKind -&gt; System.Fabric.UpgradeSafetyCheck" Usage="new System.Fabric.UpgradeSafetyCheck kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.UpgradeSafetyCheckKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para><span data-ttu-id="8a045-102">安全性チェックの種類。</span><span class="sxs-lookup"><span data-stu-id="8a045-102">The kind of the safety check.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8a045-103"><see cref="T:System.Fabric.UpgradeSafetyCheck" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8a045-103">Initializes a new instance of the <see cref="T:System.Fabric.UpgradeSafetyCheck" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeSafetyCheckKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.UpgradeSafetyCheckKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.UpgradeSafetyCheck.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As UpgradeSafetyCheckKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.UpgradeSafetyCheckKind" Usage="System.Fabric.UpgradeSafetyCheck.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8a045-104">実行中の安全性チェックの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="8a045-104">Gets the type of the safety check that is being performed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8a045-105">実行中の安全性チェックの種類。</span><span class="sxs-lookup"><span data-stu-id="8a045-105">The type of the safety check that is being performed.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>