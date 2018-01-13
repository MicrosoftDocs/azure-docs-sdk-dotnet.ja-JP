<Type Name="IWithApplication" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication">
  <TypeSignature Language="C#" Value="public interface IWithApplication" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplication" />
  <TypeSignature Language="F#" Value="type IWithApplication = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            バッチのアプリケーションの作成を許可するバッチ アカウント定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.DefineNewApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplication (applicationId As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;" Usage="iWithApplication.DefineNewApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId">アプリケーションの参照名。</param>
        <summary>
            Batch アカウントに作成されるアプリケーションの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>バッチのアプリケーション定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.UpdateApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithApplication.UpdateApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId">更新するアプリケーションの参照名。</param>
        <summary>
            この Batch アカウントの既存のバッチ アプリケーションの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>バッチのアプリケーションの更新プログラムの最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.WithoutApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithApplication.WithoutApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId">削除するアプリケーションの参照名です。</param>
        <summary>
            Batch アカウントから、指定したアプリケーションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>