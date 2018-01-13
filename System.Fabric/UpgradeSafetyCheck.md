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
      <para>現在実行されているノードのアップグレード中に安全性チェックを表します。</para>
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
          <para>安全性チェックの種類。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.UpgradeSafetyCheck" /> クラスの新しいインスタンスを初期化します。</para>
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
          <para>実行中の安全性チェックの種類を取得します。</para>
        </summary>
        <value>
          <para>実行中の安全性チェックの種類。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>