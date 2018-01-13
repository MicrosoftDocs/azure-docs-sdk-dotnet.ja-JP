<Type Name="ServicePartitionResolutionChange" FullName="System.Fabric.ServicePartitionResolutionChange">
  <TypeSignature Language="C#" Value="public sealed class ServicePartitionResolutionChange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePartitionResolutionChange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePartitionResolutionChange" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChange = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="0443c-101">このラッパーが含まれていますが、更新された<see cref="T:System.Fabric.ResolvedServicePartition" />です。</span><span class="sxs-lookup"><span data-stu-id="0443c-101">This wrapper contains the updated <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="0443c-102">新しいの中にスローされる例外が発生しました<see cref="T:System.Fabric.ResolvedServicePartition" />取得されると、次に、<see cref="T:System.Fabric.ServicePartitionResolutionChange" />も例外が含まれています。</span><span class="sxs-lookup"><span data-stu-id="0443c-102">If there was an exception thrown while the newer <see cref="T:System.Fabric.ResolvedServicePartition" /> is acquired, then the <see cref="T:System.Fabric.ServicePartitionResolutionChange" /> also contains the exception.</span></span> <span data-ttu-id="0443c-103">されている場合、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" />プロパティが null でない、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" />プロパティが null です。</span><span class="sxs-lookup"><span data-stu-id="0443c-103">Note that if the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> property is not null, then the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> property is null.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0443c-104">関連するときにスローされた例外を取得<see cref="T:System.Fabric.ResolvedServicePartition" />取得中または更新されました。</span><span class="sxs-lookup"><span data-stu-id="0443c-104">Gets the exception that was thrown while the relevant <see cref="T:System.Fabric.ResolvedServicePartition" /> was being acquired or updated.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0443c-105"><see cref="T:System.Exception" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0443c-105">Returns <see cref="T:System.Exception" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasException">
      <MemberSignature Language="C#" Value="public bool HasException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasException As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasException : bool" Usage="System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0443c-106">例外があったかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="0443c-106">Indicates whether there was an exception.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="0443c-107"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0443c-107">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0443c-108">場合は、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" />パラメーターが null と<see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" />パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="0443c-108">If so, the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> parameter is null and the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> parameter is set.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.ResolvedServicePartition" Usage="System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0443c-109">含む、新しい<see cref="T:System.Fabric.ResolvedServicePartition" />は登録されているサービスのパーティションに関連します。</span><span class="sxs-lookup"><span data-stu-id="0443c-109">Contains the new <see cref="T:System.Fabric.ResolvedServicePartition" /> that is relevant for the registered service partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0443c-110"><see cref="T:System.Fabric.ResolvedServicePartition" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0443c-110">Returns <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>