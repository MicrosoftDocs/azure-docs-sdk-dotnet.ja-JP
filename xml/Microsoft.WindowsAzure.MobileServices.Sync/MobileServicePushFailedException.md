<Type Name="MobileServicePushFailedException" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException">
  <TypeSignature Language="C#" Value="public class MobileServicePushFailedException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePushFailedException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePushFailedException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MobileServicePushFailedException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dab6b-101">プッシュが正常に完了しない場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="dab6b-101">An exception thrown when push does not complete successfully.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePushFailedException (Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult pushResult, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult pushResult, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.#ctor(Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pushResult As MobileServicePushCompletionResult, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult * Exception -&gt; Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException (pushResult, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pushResult" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="pushResult"><span data-ttu-id="dab6b-102">プッシュ操作の結果。</span><span class="sxs-lookup"><span data-stu-id="dab6b-102">Result of push operation.</span></span></param>
        <param name="innerException"><span data-ttu-id="dab6b-103">プッシュが失敗の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="dab6b-103">Inner exception that caused the push to fail.</span></span></param>
        <summary>
            <span data-ttu-id="dab6b-104"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" /> の新しいインスタンスを初期化します</span><span class="sxs-lookup"><span data-stu-id="dab6b-104">Initializes a new instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult PushResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult PushResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.PushResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PushResult As MobileServicePushCompletionResult" />
      <MemberSignature Language="F#" Value="member this.PushResult : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.PushResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dab6b-105">プッシュ操作の結果</span><span class="sxs-lookup"><span data-stu-id="dab6b-105">Result of push operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>