<Type Name="IStorageUsage" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage">
  <TypeSignature Language="C#" Value="public interface IStorageUsage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageUsage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageUsage&#xA;Implements IHasInner(Of Usage)" />
  <TypeSignature Language="F#" Value="type IStorageUsage = interface&#xA;    interface IHasInner&lt;Usage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure ストレージ リソースの使用状況情報オブジェクトの変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
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
      <MemberSignature Language="C#" Value="public int Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Integer" />
      <MemberSignature Language="F#" Value="member this.Limit : int" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.UsageName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Fluent.Models.UsageName" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.UsageName</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As UsageUnit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            測定単位を取得します。 使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'%'、'CountsPerSecond'、'BytesPerSecond' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>