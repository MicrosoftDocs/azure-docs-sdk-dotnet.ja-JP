<Type Name="MoveCost" FullName="System.Fabric.MoveCost">
  <TypeSignature Language="C#" Value="public enum MoveCost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MoveCost extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.MoveCost" />
  <TypeSignature Language="VB.NET" Value="Public Enum MoveCost" />
  <TypeSignature Language="F#" Value="type MoveCost = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="ab888-101">レプリカの移動にかかるコストをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ab888-101">Describes the move cost of a replica.</span></span></para>
    </summary>
    <remarks>
            <span data-ttu-id="ab888-102">新しいレプリカまたはサービス インスタンスが作成されるときの移動コストの既定値で取得されます。</span><span class="sxs-lookup"><span data-stu-id="ab888-102">When a new replica or service instance is created it will get a default value for move cost.</span></span> <span data-ttu-id="ab888-103">この値は、サービスに基づいて選択されます: <list type="bullet"> <item><description>レプリカまたはサービスの既定の既定のインスタンスに移動コストは指定の<see cref="F:System.Fabric.MoveCost.Zero" />、これらのレプリカの移動がないことを意味します</description>。</item> <item><description>レプリカまたはその他のサービスの既定のインスタンスに移動コストの<see cref="F:System.Fabric.MoveCost.Low" />します。</description></item></list></span><span class="sxs-lookup"><span data-stu-id="ab888-103">This value will be selected based on the service: <list type="bullet"><item><description>For replicas or instances of default services default move cost value will be <see cref="F:System.Fabric.MoveCost.Zero" />, meaning that moving these replicas is free.</description></item><item><description>For replicas or instances of other services default move cost will be <see cref="F:System.Fabric.MoveCost.Low" />.</description></item></list></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="High" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost High = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.High" />
      <MemberSignature Language="VB.NET" Value="High" />
      <MemberSignature Language="F#" Value="High = 3" Usage="System.Fabric.MoveCost.High" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ab888-104">高位のレプリカの移動コストを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab888-104">Specifies the move cost of a replica as High.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="Low" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Low = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Low" />
      <MemberSignature Language="VB.NET" Value="Low" />
      <MemberSignature Language="F#" Value="Low = 1" Usage="System.Fabric.MoveCost.Low" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ab888-105">低とレプリカの移動コストを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab888-105">Specifies the move cost of a replica as Low.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Medium">
      <MemberSignature Language="C#" Value="Medium" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Medium = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Medium" />
      <MemberSignature Language="VB.NET" Value="Medium" />
      <MemberSignature Language="F#" Value="Medium = 2" Usage="System.Fabric.MoveCost.Medium" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ab888-106">中としてレプリカの移動コストを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab888-106">Specifies the move cost of a replica as Medium.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Zero">
      <MemberSignature Language="C#" Value="Zero" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Zero = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Zero" />
      <MemberSignature Language="VB.NET" Value="Zero" />
      <MemberSignature Language="F#" Value="Zero = 0" Usage="System.Fabric.MoveCost.Zero" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ab888-107">レプリカの移動コストが 0 であることを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab888-107">Specifies the move cost of a replica as Zero.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>