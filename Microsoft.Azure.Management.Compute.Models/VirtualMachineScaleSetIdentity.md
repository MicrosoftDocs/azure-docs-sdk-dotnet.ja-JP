<Type Name="VirtualMachineScaleSetIdentity" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セットの id です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetIdentity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId">仮想マシンのスケールのプリンシパルの id は、id を設定します。</param>
        <param name="tenantId">仮想マシンのスケールに関連付けられているテナント id を設定します。</param>
        <param name="type">仮想マシンのスケールに使用される id の種類を設定します。 現時点では、唯一サポートされている型は、'SystemAssigned' は、暗黙的に id を作成します。 使用可能な値が含まれます: 'SystemAssigned'</param>
        <summary>
            VirtualMachineScaleSetIdentity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プリンシパルの id の仮想マシン スケール セットの識別情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシン スケール セットに関連付けられているテナント id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシン スケール セットに使用される id の種類を設定します。 現時点では、唯一サポートされている型は、'SystemAssigned' は、暗黙的に id を作成します。 使用可能な値が含まれます: 'SystemAssigned'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>