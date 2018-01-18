<Type Name="ProtectionPolicy" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy">
  <TypeSignature Language="C#" Value="public class ProtectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionPolicy" />
  <TypeSignature Language="F#" Value="type ProtectionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0b20-101">バックアップ ポリシーの基本クラス。</span><span class="sxs-lookup"><span data-stu-id="c0b20-101">Base class for backup policy.</span></span> <span data-ttu-id="c0b20-102">ワークロードに固有のバックアップ ポリシーは、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="c0b20-102">Workload-specific backup policies are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c0b20-103">ProtectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0b20-103">Initializes a new instance of the ProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicy (Nullable&lt;int&gt; protectedItemsCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy.#ctor(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protectedItemsCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy protectedItemsCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="protectedItemsCount"><span data-ttu-id="c0b20-104">このポリシーに関連付けられている項目の数。</span><span class="sxs-lookup"><span data-stu-id="c0b20-104">Number of items associated with this policy.</span></span></param>
        <summary>
            <span data-ttu-id="c0b20-105">ProtectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0b20-105">Initializes a new instance of the ProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemsCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedItemsCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedItemsCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy.ProtectedItemsCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemsCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemsCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy.ProtectedItemsCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemsCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0b20-106">取得または、このポリシーに関連付けられている項目の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0b20-106">Gets or sets number of items associated with this policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>