<Type Name="ExceptionInformation" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation">
  <TypeSignature Language="C#" Value="public sealed class ExceptionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionInformation" />
  <TypeSignature Language="F#" Value="type ExceptionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="77042-101">通信チャネルに表示される例外とその例外を処理するために必要な追加の情報をカプセル化するクラスを指定します。</span><span class="sxs-lookup"><span data-stu-id="77042-101">Specifies the class that encapsulates the exception seen on the communication channel and additional information required to handle that exception.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionInformation (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.#ctor(System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation : Exception -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exception" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="77042-102">受信した例外</span><span class="sxs-lookup"><span data-stu-id="77042-102">The exception that was received</span></span></param>
        <summary>
            <span data-ttu-id="77042-103">指定した例外と、既定のターゲット レプリカ セレクターを使用して、例外情報をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="77042-103">Instantiates the exception information using the given exception and the default target replica selector.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionInformation (Exception exception, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.#ctor(System.Exception,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation : Exception * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation (exception, targetReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="targetReplica" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="77042-104">受信した例外</span><span class="sxs-lookup"><span data-stu-id="77042-104">The exception that was received</span></span></param>
        <param name="targetReplica"><span data-ttu-id="77042-105">ターゲット レプリカ情報</span><span class="sxs-lookup"><span data-stu-id="77042-105">The target replica information</span></span></param>
        <summary>
            <span data-ttu-id="77042-106">指定した例外とターゲット レプリカ セレクターを使用して、例外情報をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="77042-106">Instantiates the exception information using the given exception and target replica selector.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77042-107">通信チャネルに表示された例外</span><span class="sxs-lookup"><span data-stu-id="77042-107">Exception that was seen on the communication channel</span></span>
            </summary>
        <value><span data-ttu-id="77042-108"><see cref="T:System.Exception" />が表示されます。</span><span class="sxs-lookup"><span data-stu-id="77042-108">The <see cref="T:System.Exception" /> that was seen.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplica">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplica" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.TargetReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplica As TargetReplicaSelector" />
      <MemberSignature Language="F#" Value="member this.TargetReplica : Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation.TargetReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77042-109">通信チャネルが確立されましたターゲット レプリカの識別子です。</span><span class="sxs-lookup"><span data-stu-id="77042-109">The target replica identifier to which the communication channel was established.</span></span>
            </summary>
        <value><span data-ttu-id="77042-110">A<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />ターゲット レプリカの情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="77042-110">A <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" /> that specifies gives information about the target replica</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>