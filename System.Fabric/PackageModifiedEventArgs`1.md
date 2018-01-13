<Type Name="PackageModifiedEventArgs&lt;TPackage&gt;" FullName="System.Fabric.PackageModifiedEventArgs&lt;TPackage&gt;">
  <TypeSignature Language="C#" Value="public sealed class PackageModifiedEventArgs&lt;TPackage&gt; : EventArgs where TPackage : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PackageModifiedEventArgs`1&lt;class TPackage&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageModifiedEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PackageModifiedEventArgs(Of TPackage)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt; = class&#xA;    inherit EventArgs" />
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
              変更されたパッケージの型。
            </typeparam>
    <summary>
              パッケージの変更のイベント引数を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageModifiedEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageModifiedEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
              <see cref="T:System.Fabric.PackageModifiedEventArgs`1" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewPackage">
      <MemberSignature Language="C#" Value="public TPackage NewPackage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage NewPackage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageModifiedEventArgs`1.NewPackage" />
      <MemberSignature Language="VB.NET" Value="Public Property NewPackage As TPackage" />
      <MemberSignature Language="F#" Value="member this.NewPackage : 'Package with get, set" Usage="System.Fabric.PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt;.NewPackage" />
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
              取得または新しいパッケージを設定します。
            </summary>
        <value>
          <para>古いパッケージを置換する新しいパッケージです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OldPackage">
      <MemberSignature Language="C#" Value="public TPackage OldPackage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage OldPackage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageModifiedEventArgs`1.OldPackage" />
      <MemberSignature Language="VB.NET" Value="Public Property OldPackage As TPackage" />
      <MemberSignature Language="F#" Value="member this.OldPackage : 'Package with get, set" Usage="System.Fabric.PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt;.OldPackage" />
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
              取得または変更された古いパッケージを設定します。
            </summary>
        <value>
          <para>変更された古いパッケージです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>