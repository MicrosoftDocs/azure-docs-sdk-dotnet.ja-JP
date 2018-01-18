<Type Name="ServiceBusPlugin" FullName="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin">
  <TypeSignature Language="C#" Value="public abstract class ServiceBusPlugin" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceBusPlugin extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceBusPlugin" />
  <TypeSignature Language="F#" Value="type ServiceBusPlugin = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4872-101">このクラスは、カスタム プラグインを機能にメッセージを操作するためにオーバーライドできますメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d4872-101">This class provides methods that can be overridden to manipulate messages for custom plugin functionality.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceBusPlugin ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AfterMessageReceive">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; AfterMessageReceive (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; AfterMessageReceive(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.AfterMessageReceive(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member AfterMessageReceive : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.AfterMessageReceive : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="serviceBusPlugin.AfterMessageReceive message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="d4872-102"><see cref="T:Microsoft.Azure.ServiceBus.Message" />プラグインによって変更するには</span><span class="sxs-lookup"><span data-stu-id="d4872-102">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> to be modified by the plugin</span></span></param>
        <summary>
            <span data-ttu-id="d4872-103">メッセージを受信すると後に、返される前に、この操作を呼び出す、<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="d4872-103">This operation is called after a message is received, but before it is returned to the <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d4872-104">変更されました。<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="d4872-104">The modified <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeMessageSend">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; BeforeMessageSend (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; BeforeMessageSend(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.BeforeMessageSend(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member BeforeMessageSend : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.BeforeMessageSend : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="serviceBusPlugin.BeforeMessageSend message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="d4872-105"><see cref="T:Microsoft.Azure.ServiceBus.Message" />プラグインによって変更するには</span><span class="sxs-lookup"><span data-stu-id="d4872-105">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> to be modified by the plugin</span></span></param>
        <summary>
            <span data-ttu-id="d4872-106">この操作は、メッセージが送信される前に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="d4872-106">This operation is called before a message is sent.</span></span>
            </summary>
        <returns><span data-ttu-id="d4872-107">変更されました。<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="d4872-107">The modified <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public abstract string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4872-108"><see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="d4872-108">Gets the name of the <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="d4872-109">この名前は、プラグインを特定し、プラグインが複数回登録されていることを防ぐに使用されます。</span><span class="sxs-lookup"><span data-stu-id="d4872-109">This name is used to identify the plugin, and prevent a plugin from being registered multiple times.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldContinueOnException">
      <MemberSignature Language="C#" Value="public virtual bool ShouldContinueOnException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldContinueOnException" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.ShouldContinueOnException" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ShouldContinueOnException As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldContinueOnException : bool" Usage="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.ShouldContinueOnException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4872-110">指定するかどうか、プラグインで例外が発生する必要があります、送信を防止または受信操作またはします。</span><span class="sxs-lookup"><span data-stu-id="d4872-110">Determines whether or an exception in the plugin should prevent a send or receive operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>