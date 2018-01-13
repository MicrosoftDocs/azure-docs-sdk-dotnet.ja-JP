<Type Name="NotifyTransactionChangedEventArgs" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs">
  <TypeSignature Language="C#" Value="public class NotifyTransactionChangedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyTransactionChangedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyTransactionChangedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyTransactionChangedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ad52c-101">トランザクションのイベント引数。</span><span class="sxs-lookup"><span data-stu-id="ad52c-101">Event arguments for transactions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyTransactionChangedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.#ctor(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, action As NotifyTransactionChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs (transaction, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction" />
      </Parameters>
      <Docs>
        <param name="transaction"><span data-ttu-id="ad52c-102">変更に関連するトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="ad52c-102">Transaction that the change is related to.</span></span></param>
        <param name="action"><span data-ttu-id="ad52c-103">通知の種類。</span><span class="sxs-lookup"><span data-stu-id="ad52c-103">The type of notification.</span></span></param>
        <summary>
            <span data-ttu-id="ad52c-104">新しいインスタンスを初期化します<cref name="NotifyStateManagerSingleEntityChangedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="ad52c-104">Initializes a new instance of the <cref name="NotifyStateManagerSingleEntityChangedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyTransactionChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad52c-105">イベントが作成されたアクションの種類。</span><span class="sxs-lookup"><span data-stu-id="ad52c-105">Type of action for which the event was created.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ad52c-106">通知の種類。</span><span class="sxs-lookup"><span data-stu-id="ad52c-106">The type of notification.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction Transaction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.ITransaction Transaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Transaction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transaction As ITransaction" />
      <MemberSignature Language="F#" Value="member this.Transaction : Microsoft.ServiceFabric.Data.ITransaction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Transaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad52c-107">トランザクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="ad52c-107">Gets the transaction.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ad52c-108">操作に関連付けられているトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="ad52c-108">The transaction associated with the operation.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>