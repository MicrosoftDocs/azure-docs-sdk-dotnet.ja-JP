<Type Name="INetworkUsage" FullName="Microsoft.Azure.Management.Network.Fluent.INetworkUsage">
  <TypeSignature Language="C#" Value="public interface INetworkUsage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkUsage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetworkUsage" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkUsage&#xA;Implements IHasInner(Of Usage)" />
  <TypeSignature Language="F#" Value="type INetworkUsage = interface&#xA;    interface IHasInner&lt;Usage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;</InterfaceName>
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
      <MemberSignature Language="C#" Value="public long CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int64" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.UsageName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Network.Fluent.Models.UsageName" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.UsageName</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.NetworkUsageUnit Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.NetworkUsageUnit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As NetworkUsageUnit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Network.Fluent.Models.NetworkUsageUnit" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.NetworkUsageUnit</ReturnType>
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