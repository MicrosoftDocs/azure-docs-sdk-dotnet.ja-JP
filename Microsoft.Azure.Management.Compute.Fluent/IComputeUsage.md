<Type Name="IComputeUsage" FullName="Microsoft.Azure.Management.Compute.Fluent.IComputeUsage">
  <TypeSignature Language="C#" Value="public interface IComputeUsage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeUsage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IComputeUsage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeUsage&#xA;Implements IHasInner(Of Usage)" />
  <TypeSignature Language="F#" Value="type IComputeUsage = interface&#xA;    interface IHasInner&lt;Usage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure の不変のクライアント側表現は、リソース使用状況情報オブジェクトを計算します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプションに割り当てられたリソースの現在の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプションで割り当てることができるリソースの最大数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.UsageName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Compute.Fluent.Models.UsageName" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用法の種類の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ComputeUsageUnit Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ComputeUsageUnit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As ComputeUsageUnit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Compute.Fluent.Models.ComputeUsageUnit" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ComputeUsageUnit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            測定単位を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>