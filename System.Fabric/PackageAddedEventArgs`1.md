<Type Name="PackageAddedEventArgs&lt;TPackage&gt;" FullName="System.Fabric.PackageAddedEventArgs&lt;TPackage&gt;">
  <TypeSignature Language="C#" Value="public sealed class PackageAddedEventArgs&lt;TPackage&gt; : EventArgs where TPackage : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PackageAddedEventArgs`1&lt;class TPackage&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageAddedEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PackageAddedEventArgs(Of TPackage)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type PackageAddedEventArgs&lt;'Package (requires 'Package : null)&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TPackage">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Small class.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="TPackage">
      <para>説明されているパッケージの種類です。 参照してください<see cref="T:System.Fabric.CodePackage" />、 <see cref="T:System.Fabric.ConfigurationPackage" />、<see cref="T:System.Fabric.DataPackage" />です。</para>
    </typeparam>
    <summary>
      <para>パッケージの追加されたイベントをについて説明します。 </para>
    </summary>
    <remarks>
      <para><see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" />、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" />、および <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" /> を参照してください。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageAddedEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageAddedEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
          <see cref="T:System.Fabric.PackageAddedEventArgs`1" /> クラスの新しいインスタンスを作成します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Package">
      <MemberSignature Language="C#" Value="public TPackage Package { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage Package" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageAddedEventArgs`1.Package" />
      <MemberSignature Language="VB.NET" Value="Public Property Package As TPackage" />
      <MemberSignature Language="F#" Value="member this.Package : 'Package with get, set" Usage="System.Fabric.PackageAddedEventArgs&lt;'Package (requires 'Package : null)&gt;.Package" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TPackage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービス マニフェストに追加されたコード、データ、または構成パッケージを設定します。</para>
        </summary>
        <value>
          <para>サービス マニフェストに追加されたコード、データ、または構成パッケージです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>