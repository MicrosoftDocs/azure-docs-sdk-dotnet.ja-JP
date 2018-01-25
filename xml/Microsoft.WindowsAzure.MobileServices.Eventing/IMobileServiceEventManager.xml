<Type Name="IMobileServiceEventManager" FullName="Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager">
  <TypeSignature Language="C#" Value="public interface IMobileServiceEventManager : IObservable&lt;Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceEventManager implements class System.IObservable`1&lt;class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceEventManager&#xA;Implements IObservable(Of IMobileServiceEvent)" />
  <TypeSignature Language="F#" Value="type IMobileServiceEventManager = interface&#xA;    interface IObservable&lt;IMobileServiceEvent&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IObservable&lt;Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d18ec-101">イベント通知とサブスクリプションを管理します。</span><span class="sxs-lookup"><span data-stu-id="d18ec-101">Manages event notifications and subscriptions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PublishAsync (Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent mobileServiceEvent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PublishAsync(class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent mobileServiceEvent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager.PublishAsync(Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent)" />
      <MemberSignature Language="VB.NET" Value="Public Function PublishAsync (mobileServiceEvent As IMobileServiceEvent) As Task" />
      <MemberSignature Language="F#" Value="abstract member PublishAsync : Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceEventManager.PublishAsync mobileServiceEvent" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mobileServiceEvent" Type="Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent" />
      </Parameters>
      <Docs>
        <param name="mobileServiceEvent"><span data-ttu-id="d18ec-102">公開するイベントです。</span><span class="sxs-lookup"><span data-stu-id="d18ec-102">The event to be published.</span></span></param>
        <summary>
            <span data-ttu-id="d18ec-103">発行、<see cref="T:Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent" />です。</span><span class="sxs-lookup"><span data-stu-id="d18ec-103">Publishes a <see cref="T:Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d18ec-104">イベントが発行されたときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="d18ec-104">A task that completes when the event is published.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscribe&lt;T&gt;">
      <MemberSignature Language="C#" Value="public IDisposable Subscribe&lt;T&gt; (Action&lt;T&gt; next) where T : class, Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IDisposable Subscribe&lt;class (class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent) T&gt;(class System.Action`1&lt;!!T&gt; next) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager.Subscribe``1(System.Action{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Subscribe(Of T As {Class, IMobileServiceEvent}) (next As Action(Of T)) As IDisposable" />
      <MemberSignature Language="F#" Value="abstract member Subscribe : Action&lt;'T (requires 'T : null and 'T :&gt; Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent)&gt; -&gt; IDisposable (requires 'T : null and 'T :&gt; Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent)" Usage="iMobileServiceEventManager.Subscribe next" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IDisposable</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEvent</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="next" Type="System.Action&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="d18ec-105">通知をフィルターするイベントの基本データ型。</span><span class="sxs-lookup"><span data-stu-id="d18ec-105">The base type of event to filter notifications by.</span></span></typeparam>
        <param name="next"><span data-ttu-id="d18ec-106">イベントの処理に呼び出されるデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d18ec-106">The delegate to be invoked to handle events.</span></span></param>
        <summary>
            <span data-ttu-id="d18ec-107">イベント通知をサブスクライブします。</span><span class="sxs-lookup"><span data-stu-id="d18ec-107">Subscribes to event notifications.</span></span>
            </summary>
        <returns><span data-ttu-id="d18ec-108"><see cref="T:System.IDisposable" />サブスクリプションを表すインスタンス。</span><span class="sxs-lookup"><span data-stu-id="d18ec-108">An <see cref="T:System.IDisposable" /> instance representing the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>