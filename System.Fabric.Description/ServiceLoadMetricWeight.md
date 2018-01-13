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
      <para>メトリックの重みをについて説明します。</para>
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
          <para>高位のサービスの負荷メトリックの重みを指定します。</para>
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
          <para>Low として、サービスの負荷のメトリックの重みを指定します。</para>
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
          <para>メディアとして、サービスの負荷のメトリックの重みを指定します。</para>
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
          <para>0 と、サービスの負荷のメトリックの重みを指定します。 この指標の Service Fabric 負荷分散を無効にします。 実行時にバランスがくずれていますメトリックでであってもできるノード上の容量を制御する、まだことができますが、によって報告されます<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />です。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>