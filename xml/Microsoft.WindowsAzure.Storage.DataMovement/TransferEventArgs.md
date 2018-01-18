<Type Name="TransferEventArgs" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs">
  <TypeSignature Language="C#" Value="public sealed class TransferEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TransferEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TransferEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type TransferEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2087e-101">イベントの引数を転送します。</span><span class="sxs-lookup"><span data-stu-id="2087e-101">Transfer event args.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferEventArgs (object source, object destination);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object source, object destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.#ctor(System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Object, destination As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs : obj * obj -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs (source, destination)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="destination" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="2087e-102">転送元の場所のインスタンスの表現。</span><span class="sxs-lookup"><span data-stu-id="2087e-102">Instance representation of transfer source location.</span></span></param>
        <param name="destination"><span data-ttu-id="2087e-103">転送先の場所のインスタンスの表現。</span><span class="sxs-lookup"><span data-stu-id="2087e-103">Instance representation of transfer destination location.</span></span></param>
        <summary>
            <span data-ttu-id="2087e-104"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2087e-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public object Destination { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Destination" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Destination As Object" />
      <MemberSignature Language="F#" Value="member this.Destination : obj" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2087e-105">転送のインスタンス形式を移行先の場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="2087e-105">Gets the instance representation of transfer destination location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2087e-106">取得では、終了時刻を転送します。</span><span class="sxs-lookup"><span data-stu-id="2087e-106">Gets transfer end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2087e-107">転送が成功した場合、転送が失敗した、または null の場合は、例外を取得します。</span><span class="sxs-lookup"><span data-stu-id="2087e-107">Gets the exception if the transfer is failed, or null if the transfer is success.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public object Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As Object" />
      <MemberSignature Language="F#" Value="member this.Source : obj" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2087e-108">ソースの場所に転送のインスタンスの表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="2087e-108">Gets the instance representation of transfer source location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2087e-109">取得では、開始時刻を転送します。</span><span class="sxs-lookup"><span data-stu-id="2087e-109">Gets transfer start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>