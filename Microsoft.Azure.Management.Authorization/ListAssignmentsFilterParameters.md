<Type Name="ListAssignmentsFilterParameters" FullName="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters">
  <TypeSignature Language="C#" Value="public class ListAssignmentsFilterParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ListAssignmentsFilterParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ListAssignmentsFilterParameters" />
  <TypeSignature Language="F#" Value="type ListAssignmentsFilterParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ロール割り当てフィルターの一覧です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListAssignmentsFilterParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ListAssignmentsFilterParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssignedToPrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AssignedToPrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AssignedToPrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AssignedToPrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property AssignedToPrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AssignedToPrincipalId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AssignedToPrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 プリンシパルと、プリンシパルのグループ (推移的) への割り当てに直接割り当てられたロールの割り当てを返します。 ユーザー プリンシパルでのみサポートは、現在、
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtScope">
      <MemberSignature Language="C#" Value="public bool AtScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AtScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AtScope" />
      <MemberSignature Language="VB.NET" Value="Public Property AtScope As Boolean" />
      <MemberSignature Language="F#" Value="member this.AtScope : bool with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AtScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 以上であるすべてのロールの割り当てが返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property PrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 特定のプリンシパルの役割の割り当てを返します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>