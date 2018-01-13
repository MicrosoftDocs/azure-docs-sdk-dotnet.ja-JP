<Type Name="ServiceLoadMetricWeight" FullName="System.Fabric.Description.ServiceLoadMetricWeight">
  <TypeSignature Language="C#" Value="public enum ServiceLoadMetricWeight" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceLoadMetricWeight extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceLoadMetricWeight" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceLoadMetricWeight" />
  <TypeSignature Language="F#" Value="type ServiceLoadMetricWeight = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="03537-101">メトリックの重みをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="03537-101">Describes the weight of a metric.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="High" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceLoadMetricWeight High = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceLoadMetricWeight.High" />
      <MemberSignature Language="VB.NET" Value="High" />
      <MemberSignature Language="F#" Value="High = 3" Usage="System.Fabric.Description.ServiceLoadMetricWeight.High" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="03537-102">高位のサービスの負荷メトリックの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="03537-102">Specifies the metric weight of the service load as High.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="Low" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceLoadMetricWeight Low = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceLoadMetricWeight.Low" />
      <MemberSignature Language="VB.NET" Value="Low" />
      <MemberSignature Language="F#" Value="Low = 1" Usage="System.Fabric.Description.ServiceLoadMetricWeight.Low" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="03537-103">Low として、サービスの負荷のメトリックの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="03537-103">Specifies the metric weight of the service load as Low.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Medium">
      <MemberSignature Language="C#" Value="Medium" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceLoadMetricWeight Medium = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceLoadMetricWeight.Medium" />
      <MemberSignature Language="VB.NET" Value="Medium" />
      <MemberSignature Language="F#" Value="Medium = 2" Usage="System.Fabric.Description.ServiceLoadMetricWeight.Medium" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="03537-104">メディアとして、サービスの負荷のメトリックの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="03537-104">Specifies the metric weight of the service load as Medium.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Zero">
      <MemberSignature Language="C#" Value="Zero" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceLoadMetricWeight Zero = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceLoadMetricWeight.Zero" />
      <MemberSignature Language="VB.NET" Value="Zero" />
      <MemberSignature Language="F#" Value="Zero = 0" Usage="System.Fabric.Description.ServiceLoadMetricWeight.Zero" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="03537-105">0 と、サービスの負荷のメトリックの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="03537-105">Specifies the metric weight of the service load as Zero.</span></span> <span data-ttu-id="03537-106">この指標の Service Fabric 負荷分散を無効にします。</span><span class="sxs-lookup"><span data-stu-id="03537-106">Disable Service Fabric Load Balancing for this metric.</span></span> <span data-ttu-id="03537-107">実行時にバランスがくずれていますメトリックでであってもできるノード上の容量を制御する、まだことができますが、によって報告されます<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />です。</span><span class="sxs-lookup"><span data-stu-id="03537-107">Note that metrics that are not balanced during runtime can still be used to control capacity on nodes and can still be reported via <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>